<template>
  <div class="about flex" >
    <h1>This is an about page</h1>
  </div>
  <BigPicture :imgurl="1"></BigPicture>

  <div class="flex" v-for="item in 5" :key="item">
    <BigPicture :imgurl="item"></BigPicture> 

    {{item}}
  </div>

</template>



<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import BigPicture from '@/components/BigPicture.vue'

export default {
  name: 'AboutView',
  components: {
    HelloWorld, BigPicture
  }
}
</script>

<Style  lang="scss">
.flex{
  display:flex;
  width:100%;
  border : 1px solid darkcyan;
}
</Style>