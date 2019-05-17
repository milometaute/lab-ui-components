<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="container">
      <div class="row">
        <div class="col-9">
          <p>I write code</p>
          
        </div>
        <div class="col-3">
          <a class="d-block" href="">Markup Challenge</a>
          <a class="d-block" href="">UI components with code</a>
          <a class="d-block" href="">Microinteractions with code</a>
          <a class="d-block" href="">Transitions and effects with code</a>
        </div>
      </div>

      <div class="row">
        <div class="col-3">
          <a class="d-block" href="">Markup Challenge</a>
          <a class="d-block" href="">UI components with code</a>
          <a class="d-block" href="">Microinteractions with code</a>
          <a class="d-block" href="">Transitions and effects with code</a>
        </div>
        <div class="col-9">
          <p>I create Design</p>
        </div>
      </div>

      <div class="row">
        <div class="col-9">
          <p>I make Interactions</p>
        </div>
        <div class="col-3">
          <a class="d-block" href="">Markup Challenge</a>
          <a class="d-block" href="">UI components with code</a>
          <a class="d-block" href="">Microinteractions with code</a>
          <a class="d-block" href="">Transitions and effects with code</a>
        </div>
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
</style>
