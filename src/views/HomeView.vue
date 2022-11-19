<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <HelloWorld msg="嘿嘿" button="嘿嘿嘿嘿"/>
    <HelloWorld msg="嘿嘿吼吼"/>
    <HelloWorld msg="嘿嘿哈哈"/>
    <HelloWorld msg="嘿嘿" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
