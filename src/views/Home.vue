<template>
  <div class="home">
    <img width ="1400" alt="" src="https://www.earticleblog.com/wp-content/uploads/2017/08/gp-amazon-sale-banner-29062017.jpg">
    <HelloWorld msg="BEST DEALS "/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'



export default {
  name: 'Home',
  components: {
    HelloWorld,
    
  }
}
</script>
