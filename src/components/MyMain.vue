<template>
  <div>
    <Main>
        <BrowseByCategory />
        <NewArrivals />
        <TestimonialsNewsLetter />
        <TipsTricks />
        <NewProducts />
    </Main>
  </div>
</template>

<script>
import BrowseByCategory from "./partials/PartialsMain/BrowseByCategory.vue" 
import NewArrivals from "./partials/PartialsMain/NewArrivals.vue" 
import TestimonialsNewsLetter from "./partials/PartialsMain/TestimonialsNewsLetter.vue" 
import TipsTricks from "./partials/PartialsMain/TipsTricks.vue" 
import NewProducts from "./partials/PartialsMain/NewProducts.vue" 






export default {
  name: "MyMain",
  components:{
    BrowseByCategory,
    NewArrivals,
    TestimonialsNewsLetter,
    TipsTricks,
    NewProducts,
  }
};
</script>

<style lang="scss" scoped>

</style>