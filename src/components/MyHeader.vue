<template>
  <div>
    <header>
        <h1>
            My Header
        </h1>

    <UpperHeader/>
    <LowerHeader />

    </header>
  </div>
</template>

<script>
import UpperHeader from "./partials/UpperHeader.vue" 
import LowerHeader from "./partials/LowerHeader.vue" 


export default {
  name: "MyHeader",
  components:{
    UpperHeader,
    LowerHeader,
  }
};
</script>

<style lang="scss" scoped>

</style>
