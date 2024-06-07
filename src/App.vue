<script>
import AppTitle from "./components/AppTitle.vue";
import AppMainContent from "./components/AppMainContent.vue"
import AppFooter from "./components/AppFooter.vue"
export default {
  components :{
    AppTitle ,
    AppMainContent ,
    AppFooter,
  },
  data() {
    return {
      msg : "", 
    }
  }
}
</script>

<template>
  
  <main>
      <AppTitle />
      <AppMainContent />
      <AppFooter />
  </main>

</template>

<style scoped>

</style>
