<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-12">
        <h4>Code</h4>
        <ul class="d-flex justify-content-around">
          <li class="list-unstyled">Markup Challenge (HTML5 & CSS3)</li>
          <li class="list-unstyled">UI components (VueJs)</li>
          <li class="list-unstyled">Transitions (CSS3 & JS)</li>
          <li class="list-unstyled">Effects (JS)</li>
        </ul>
      </div>
    </div>
    <div class="row">
      <div class="col-12">
        <h3>Markup Challenge</h3>
        {{miniData}}
      </div>
    </div>
    <div class="container-challenges">

    </div>
  </div>
</template>
<script>
  export default {
    name: "codeComponent",
    props: {
      miniData: ''
    }
  }
</script>

<style scoped>
  .container-challenges {
    background-color: lightblue;
    height: 100vh;
  }
</style>
