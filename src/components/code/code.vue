<template>
  <div class="row">
    <div class="col-12">
      <h3>Código</h3>
      {{miniData}}
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
