<template>
  <div id="app">
    <div class="main-content" style="height: 100vh;background-color: #686de0;">
      
      <div class="d-flex align-items-center py-3 lc-navbar">
        <img alt="Vue logo" class="ml-3 mr-auto" height="60px" src="http://milometaute.com/wp-content/uploads/2018/06/logo-milometaute-02.png">
        <div id="nav">
          <router-link to="/">About</router-link> |
          <router-link to="/about">Work</router-link> |
          <router-link to="/about">Articles</router-link>
        </div>
      </div>

      <div class="d-flex align-items-center lc-header">
        <div class="text-left mx-3">
          <h1 class="w-100 py-0 my-0 display-2"> <span class="d-block">Camilo Metaute</span>  <span class="d-block">UI Designer</span> </h1>
          <span class="w-100">This is Lab Components, my training space with Code - Design - Ideas</span>
        </div>
      </div>

      <div class="d-flex flex-wrap flex-md-nowrap w-75 lc-bottom-menu">
        <div class="flex-1 text-left p-3 mr-auto">
          <p>01</p>
          <h3>I write Code</h3>
          <span>The space where</span>
        </div>
        <div class="flex-1 text-left p-3 mr-auto">
          <p>02</p>
          <h3>I create Design</h3>
          <span>The space where</span>
        </div>
        <div class="flex-1 text-left p-3 mr-auto">
          <p>03</p>
          <h3>I make Interactions</h3>
          <span>The space where</span>
        </div>
      </div>
      
    </div>
    
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family:  'Work Sans',sans-serif, 'Playfair Display', serif;
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

h1 {
  font-family: 'Playfair Display';
};

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
