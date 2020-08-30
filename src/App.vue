<template>
  <div id="app">
    <router-view />
    <div class="navbar">
      <router-link to="/">Home</router-link>|
      <router-link to="/profile">Profile</router-link>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  display: flex;
  flex-direction: column;
  background-color: rgb(243, 243, 243);
  height: 100vh;
  width: 100%;
}
.navbar {
  height: 10%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #fff;
}
.header {
  height: 5%;
  text-align: center;
  margin: 10px 0;
}
.header > h1 {
  margin: auto;
}

body {
  padding: 0;
  margin: 0;
}
</style>
