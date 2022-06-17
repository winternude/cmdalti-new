<template>
  <div class ="navbar"><p>This is a Div Wow a new div</p></div>
  <nav>
    <router-link to="/">Never Go Home</router-link> |
    <router-link to="/about">Give me a reason</router-link>
  </nav>
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

.navbar {
width: 100vw;
height: 40px;
background-color: grey;

}
</style>
