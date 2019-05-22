<template>
  <div class="container-fluid">
    <div class="row" style="background-color: #efefef;">
      <div class="col-12">
        <h1 class="font-size-xxxl mt-5 mb-3">{{ msg }}</h1>
        <span>You can see here my skills and the projects where I training like Designer</span>
      </div>
    </div>
    <div class="row jobs-container align-items-center">
      <div class="col-12 col-md-6">
        <h2 class="align-self-center">I write code</h2>
      </div>
      <div class="col-12 col-md-6 text-left">
        <a class="lc-btn mt-2 mb-3" href="/#/code">
          Markup Challenge (HTML5 & CSS3)
          <span class="d-block font-size-sm text-secondary mb-2">This is a personal project where I improve my skills</span>
        </a>
        <a class="lc-btn mt-2 mb-3" href="">UI components (VueJs)
          <span class="d-block font-size-sm text-secondary  mb-2">This is a personal project where I improve my skills</span>
        </a>
        <a class="lc-btn mt-2 mb-3" href="">
          Transitions (CSS3 & JS)
          <span class="d-block font-size-sm text-secondary  mb-2">Transitions betweem pages and smooth changes</span>
        </a>
        <a class="lc-btn mt-2 mb-3" href="">Effects (JS)</a>
        <span class="d-block font-size-sm text-secondary  mb-2">Parallax, scroll effects, swipes and more </span>
      </div>
    </div>

    <div class="row jobs-container align-items-center">
      <div class="col-12 col-md-6 text-right">
        <a class="lc-btn my-2" href="">Grid Challenge and Experiments ( XD - Sketch - Figma )
          <span class="d-block font-size-sm text-secondary mb-2">A space for experiments with tends, new ways to creat and more</span>
        </a>
        <a class="lc-btn my-2" href="">Design System ( Abstract - XD )
          <span class="d-block font-size-sm text-secondary mb-2">My digital space for a training camp with design system and tools</span>
        </a>
        <a class="lc-btn my-2" href="">UI Components ( XD - Figma )
          <span class="d-block font-size-sm text-secondary mb-2">Here I think about states, modifiers and transformations of elements</span>
        </a>
        <a class="lc-btn my-2" href="">Icon sets ( Illustrator )
          <span class="d-block font-size-sm text-secondary mb-2">Handly side, since the paper to the screen</span>
        </a>
      </div>
      <div class="col-12 col-md-6">
        <h2 class="align-self-center">I Design</h2>
      </div>
    </div>

    <div class="row jobs-container align-items-center">
      <div class="col-12 col-md-6">
        <h2 class="align-self-center">I create Interactions</h2>
      </div>
      <div class="col-12 col-md-6 text-left">
        <a class="lc-btn my-2" href="">Landings UI movements (Protopie.io)
          <span class="d-block font-size-sm text-secondary mb-2">A space for experiments with tends, new ways to creat and more</span>
        </a>
        <a class="lc-btn my-2" href="">Microinteractions (Protopie.io)
          <span class="d-block font-size-sm text-secondary mb-2">My digital space for a training camp with design system and tools</span>
        </a>
        <a class="lc-btn my-2" href="">Concepts UI (Protopie.io & Invision Studio)
          <span class="d-block font-size-sm text-secondary mb-2">Here I think about states, modifiers and transformations of elements</span>
        </a>
        <a class="lc-btn my-2" href="">Loadings with icons and more
          <span class="d-block font-size-sm text-secondary mb-2">Handly side, since the paper to the screen</span>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }

  .jobs-container {
    height: 100vh;
    background-color:#efefef;
  }
</style>
