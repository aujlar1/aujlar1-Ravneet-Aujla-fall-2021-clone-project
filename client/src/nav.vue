<template>
  <Nav
  </div>
  <router-view/>
</template>
<style lang = "scss">
</style>
<script>
import Nav from "./components/Nav";
export default {
compunds:{
 data(){
     return{
         isActive: false
     }
 }
}
}
</script>