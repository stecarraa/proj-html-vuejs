<template>
  <div>
    <Main>
        <h1>
            My Main
        </h1>
        <BrowseByCategory />
    </Main>
  </div>
</template>

<script>
import BrowseByCategory from "./partials/PartialsMain/BrowseByCategory.vue" 


export default {
  name: "MyMain",
  components:{
    BrowseByCategory,
  }
};
</script>

<style lang="scss" scoped>

</style>