<template>
  <div id="app">
        <HeaderComponent />
    <router-view/>
        <FooterComponent />
  </div>
</template>


<script>
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
export default {
  components:{
     HeaderComponent,
      FooterComponent
  }
}
</script>
<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
</style>
