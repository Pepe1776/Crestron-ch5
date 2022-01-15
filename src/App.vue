<script lang="ts">
</script>

<template>
  <div id="nav">
    <div class="flex flex-col">
      <router-link to="/">
        <font-awesome-icon icon="house-damage" class="nav-link" />  Home
      </router-link>
      <router-link to="/Living">
        <font-awesome-icon icon="couch" class="nav-link" />  Living Room
      </router-link>
      <router-link to="/Bed">
        <font-awesome-icon icon="bed" class="nav-link" />  Bed Room
      </router-link>
      <router-link to="/Kitchen">
        <font-awesome-icon icon="sink" class="nav-link" />  Kitchen
      </router-link>
      <router-link to="/Family">
        <font-awesome-icon icon="dice" class="nav-link" />  Family Room
      </router-link>
    </div>
  </div>
  <div class="rv">
  <router-view />
  </div>
</template>

<style lang="scss">
html {
  margin: 0;
  padding: 0;
  font-size: 10px;
  background-color: #000000;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fbfbfb94;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    font-size: 2rem;
    color: #f8f8f894;
    margin-left: -40%;
    width: 100%;

    &.router-link-exact-active {
      color: #0d8add;
    }
  }
}
.nav-link {
  margin-top: 9%;
  left: 0;
  top: 0;
}
.rv {
  position: absolute;
  right: 0;
  top: 5rem;
  width: 100%;
  heigth: 76.8rem;
}
</style>
