<template>
  <div>
    <header>
        <h1>
            My Header
        </h1>

    <UpperHeader/>

    </header>
  </div>
</template>

<script>
import UpperHeader from "./partials/UpperHeader.vue" 

export default {
  name: "MyHeader",
  components:{
    UpperHeader,
  }
};
</script>

<style lang="scss" scoped>

</style>
