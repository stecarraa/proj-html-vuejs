<template>
  <div>
    <Main>
        <BrowseByCategory />
        <NewArrivals />
        <TestimonialsNewsLetter />
        <TipsTricks />
    </Main>
  </div>
</template>

<script>
import BrowseByCategory from "./partials/PartialsMain/BrowseByCategory.vue" 
import NewArrivals from "./partials/PartialsMain/NewArrivals.vue" 
import TestimonialsNewsLetter from "./partials/PartialsMain/TestimonialsNewsLetter.vue" 
import TipsTricks from "./partials/PartialsMain/TipsTricks.vue" 





export default {
  name: "MyMain",
  components:{
    BrowseByCategory,
    NewArrivals,
    TestimonialsNewsLetter,
    TipsTricks
  }
};
</script>

<style lang="scss" scoped>

</style>