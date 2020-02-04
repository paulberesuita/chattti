<template>
  <div class="home">
    <div class="mt-24">
      <img style="width: 150px; display: inline-block" src="../assets/chattti-logo.png">
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
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
