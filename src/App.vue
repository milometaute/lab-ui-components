<template>
  <div id="app">
    <div class="main-content" style="height: 100vh;background-repeat: no-repeat; background-size: cover; background-image:url('https://images.pexels.com/photos/196644/pexels-photo-196644.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260')">
      
      <div class="d-flex align-items-center py-3">
        <img alt="Vue logo" class="ml-3 mr-auto" height="60px" src="http://milometaute.com/wp-content/uploads/2018/06/logo-milometaute-02.png">
        <div id="nav">
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About me</router-link> |
          <router-link to="/about">Lab UI</router-link>
        </div>
      </div>

      <div class="d-flex align-items-center h-100">
        <div class="text-left mx-3">
          <h1 class="w-100 py-0 my-0">Lab Components</h1>
          <span class="w-100">A personal project with UI experiments and design lab</span>
        </div>
      </div>
    </div>
    
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
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
</style>
