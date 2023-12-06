<template>
  <nav class="flex justify-between">
    <div>
      <router-link to="/">Logo</router-link>
    </div>
    <div class="navlink">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
  </nav>
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: right;
  color: #2c3e50;
}

nav {
  padding: 30px;

  .navlink a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
  a {
    font-weight: bold;
    color: #2c3e50;
  }
}
</style>
