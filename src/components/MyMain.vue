<template>
  <div>
    <Main>
        <BrowseByCategory />
        <NewArrivals />
        <TestimonialsNewsLetter />
    </Main>
  </div>
</template>

<script>
import BrowseByCategory from "./partials/PartialsMain/BrowseByCategory.vue" 
import NewArrivals from "./partials/PartialsMain/NewArrivals.vue" 
import TestimonialsNewsLetter from "./partials/PartialsMain/TestimonialsNewsLetter.vue" 




export default {
  name: "MyMain",
  components:{
    BrowseByCategory,
    NewArrivals,
    TestimonialsNewsLetter
  }
};
</script>

<style lang="scss" scoped>

</style>