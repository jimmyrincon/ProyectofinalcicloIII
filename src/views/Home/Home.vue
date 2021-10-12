<template>
  <div id="app" class="top-container">
    <my-header>
      <carousel/>
    </my-header>
    <router-view>

    </router-view>
    <my-body>
      <Body/>
    </my-body>

    <my-footer>
      <Footer/>
    </my-footer>

  </div>    
</template>


<script>
  import Carousel from "./Components/Carousel.vue";
  import Footer from "../../components/Footer.vue";
  import Body from "../../components/Body.vue"
 
  export default {
    name: 'Home',
    components: {
      Carousel,
      Footer,
      Body, 
    }
  }
</script>
