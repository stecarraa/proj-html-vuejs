<template>
  <div>
    <Main>
        <h1>
            My Main
        </h1>
        <BrowseByCategory />
        <NewArrivals />
    </Main>
  </div>
</template>

<script>
import BrowseByCategory from "./partials/PartialsMain/BrowseByCategory.vue" 
import NewArrivals from "./partials/PartialsMain/NewArrivals.vue" 



export default {
  name: "MyMain",
  components:{
    BrowseByCategory,
    NewArrivals
  }
};
</script>

<style lang="scss" scoped>

</style>