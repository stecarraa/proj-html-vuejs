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
import UpperHeader from "./partials/PartialsHeader/UpperHeader.vue" 
import LowerHeader from "./partials/PartialsHeader/LowerHeader.vue" 
import MyJumbotron from "./partials/PartialsHeader/MyJumbotron.vue" 



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
