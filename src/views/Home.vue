<template>
  <div class="home">
    <img alt="Vue logo" width="160px" src="http://milometaute.com/wp-content/uploads/2018/06/logo-milometaute-02.png">
    <HelloWorld msg="Welcome to Lab UI Components"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
