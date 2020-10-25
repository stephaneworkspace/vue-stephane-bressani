<template>
  <!--<div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>-->
  <div class="App-header">
    <router-view class="App-header-gradient" />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #000033;
}

.App-header {
  background-image: url("./assets/bg.png");
  background-repeat: no-repeat;
  background-position: center top;
  background-color: #ffeedd;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.App-header-gradient {
  width: 1300px;
  background-image: linear-gradient(to right, #ffeedd, transparent),
    linear-gradient(to left, #ffeedd, transparent) !important;
  background-repeat: repeat-y, repeat-y;
  background-position: left top, right top;
  background-size: 30px 100%, 300px 100%;
  min-height: 100vh;
}
</style>
