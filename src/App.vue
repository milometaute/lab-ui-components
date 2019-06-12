<template>
  <div id="app">
    <div class="main-content container-fluid" style="height: 100vh;background-color: #13E4A0;">

      <div class="d-flex align-items-center py-3 px-5 lc-navbar">
        <img alt="Vue logo" class="ml-3 mr-auto" height="60px" src="http://milometaute.com/wp-content/uploads/2018/06/logo-milometaute-02.png">
        <div id="nav">
          <router-link to="/about">About</router-link> |
          <router-link to="/">Work</router-link> |
          <router-link to="/about">Articles</router-link>
        </div>
      </div>

      <div class="d-flex align-items-center lc-header">
        <div class="text-left mx-3 px-5">
          <h1 class="w-100 py-0 my-0 display-2"> <span class="d-block name">Camilo Metaute</span>  <span class="d-block  job">UI Designer</span> </h1>
          <span class="w-100">This is Lab Components, my training space with Code - Design and Ideas</span>
        </div>
      </div>

      <div class="d-flex flex-wrap flex-md-nowrap justify-content-center w-75 lc-bottom-menu px-5">
        <div class="flex-1 desk-content text-left p-3 mr-auto align-self-center">
          <p class="h3">
            <strong> 01 </strong>
          </p>
          <a class="lc-btn">I write Code</a>
          <p>The space where I can do real my designs</p>
        </div>
        <div class="flex-1 desk-content text-left p-3 mr-auto align-self-center">
          <p class="h3">
            <strong> 02 </strong>
          </p>
          <a class="lc-btn">I Design UI</a>
          <p>I begin in the paper and make this real with digital tools</p>
        </div>
        <div class="flex-1 desk-content text-left p-3 mr-auto align-self-center">
          <p class="h3">
            <strong> 03 </strong>
          </p>
          <a class="lc-btn">I create Interactions</a>
          <p>My creations getting live with animations</p>
        </div>
        <div class="flex-1 mob-content d-lg-none d-block align-self-start w-100">
          <button class="w-100 btn btn-primary">Ver mi trabajo</button>
        </div>
      </div>

      <router-view/>
    </div>
  </div>
</template>

<style>

#app {
  font-family: 'fieldwork-hum', sans-serif, 'Open Sans', sans-serif;
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
  height: 8%;
}

.lc-header {
  height: 67%;
}

.lc-header .name {
  color: white;
}

.lc-header .job {
  -webkit-text-stroke: 2px white;
  color: transparent;
  font-size: 1.2em;
}

.lc-header h1 {
  font-weight: 800;
  color: white;
}

.lc-header span {
  font-size: 1.2em;
  color: white;
}

.lc-bottom-menu{
  background-color: white;
  height: 25%;
}

.lc-btn {
  color: #42b983 !important;
  cursor: pointer;
  font-size: 1.8em;
  font-weight: 600;
  position: relative;
  text-decoration: none !important;
  transform: perspective(1px) translateZ(0);
}

.lc-btn:before {
  background: #42b983;
  bottom: -3px;
  content: "";
  height: 4px;
  left: 0;
  position: absolute;
  right: 100%;
  transition: .3s right ease-out;
  z-index: -1;
}

.lc-btn:hover:before, .lc-btn:focus:before, .lc-btn:active:before {
  right: 0;
}

/* Font Size scale
  based on: https://marvelapp.com/styleguide/design/typography */
.font-size-xxs    {font-size: 10px;}
.font-size-xs     {font-size: 12px;}
.font-size-sm     {font-size: 14px;}
.font-size-md     {font-size: 16px;}
.font-size-lg     {font-size: 18px;}
.font-size-xl     {font-size: 20px;}
.font-size-xxl    {font-size: 28px;}
.font-size-xxxl   {font-size: 38px;}
.font-size-xxxxl  {font-size: 46px;}

@media (max-width: 992px) {
  .lc-header {
    height: 85%;
  }

  .lc-header span {
    font-size: .7em;
  }

  .lc-bottom-menu {
    height: 8%;
  }

  .lc-bottom-menu .desk-content {
      display: none;
    }
}
</style>
