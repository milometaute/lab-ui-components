<template>
  <div id="app">
    <div class="main-content" style="height: 100vh;background-color: #686de0;">
      
      <div class="d-flex align-items-center py-3 lc-navbar">
        <img alt="Vue logo" class="ml-3 mr-auto" height="60px" src="http://milometaute.com/wp-content/uploads/2018/06/logo-milometaute-02.png">
        <div id="nav">
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About me</router-link> |
          <router-link to="/about">Lab UI</router-link>
        </div>
      </div>

      <div class="d-flex align-items-center lc-header">
        <div class="text-left mx-3">
          <h1 class="w-100 py-0 my-0">Lab UI Components</h1>
          <span class="w-100">A personal project with UI experiments and design lab</span>
        </div>
      </div>

      <div class="d-flex lc-bottom-menu w-75">

      </div>
    </div>
    
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Roboto', Helvetica, Arial, sans-serif;
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
  color: #42b983;
}

.lc-navbar {
  height: 10%;
}

.lc-header {
  height: 70%;
}

.lc-header h1 {
  font-size: 4em;
  font-weight: 800;
  color: white;
}

.lc-header span {
  font-size: 1.2em;
  color: white;
}

.lc-bottom-menu{
  height: 20%;
  background-color: white;
}

</style>
