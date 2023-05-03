<script>
  import AppNav from "./components/AppNav.vue"  
  import AppMain from "./components/AppMain.vue"
  import AppFooter from "./components/AppFooter.vue"

  export default{
    name:"App",
    components:{
        AppNav,
        AppMain,
        AppFooter    
    }
  }

</script>

<template>
  <div>
      <AppNav/>
      <AppMain/>
      <AppFooter/>
  </div>
  
</template>

<style lang="scss">
  @use "./style/main.scss" as *;
  
</style>
