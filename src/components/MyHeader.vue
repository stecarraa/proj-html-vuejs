<template>
  <div>
    <header>
       
    <UpperHeader/>
    <LowerHeader />
    <MyJumbotron/>

    </header>
  </div>
</template>

<script>
import UpperHeader from "./partials/UpperHeader.vue" 
import LowerHeader from "./partials/LowerHeader.vue" 
import MyJumbotron from "./partials/MyJumbotron.vue" 



export default {
  name: "MyHeader",
  components:{
    UpperHeader,
    LowerHeader,
    MyJumbotron
  }
};
</script>

<style lang="scss" scoped>

</style>
