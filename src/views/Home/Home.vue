<template>
<div id="app" class="top-container">
  <my-header>
    <carousel/>
  </my-header>
  <router-view>

    
  </router-view>
 
</div>    
</template>


<script>
  import Carousel from "./Components/Carousel.vue";
  
 
  export default {
    name: 'Home',
    components: {
      Carousel
      
      
      }, 
  }
</script>