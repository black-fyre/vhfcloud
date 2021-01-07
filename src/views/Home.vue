<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <TheFooter></TheFooter>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import TheFooter from "@/components/TheFooter";

export default {
  name: 'Home',
  components: {
    TheFooter,
    HelloWorld
  }
}
</script>
