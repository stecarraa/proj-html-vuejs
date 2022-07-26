<template>
  <div class="ms-container">
        <ul class="list-unstyled d-flex justify-content-between">
            <li  v-for="(item, index) in navItems" :key="index">
                <a class="text-decoration-none text-secondary" :href="item.url">{{item.name}}</a>
            </li>
        </ul>

  </div>
</template>

<script>
export default {
  name: "LowerHeader",
  data : function(){
        return{
            navItems : [
                {
                    name : "Home",
                    url : "#"
                },
                {
                    name : "Shop",
                    url : "#"
                },
                {
                    name : "About",
                    url : "#"
                },
                {
                    name : "Blog",
                    url : "#"
                },
                {
                    name : "Contact",
                    url : "#"
                },
                 {
                    name : "Shop By Brand",
                    url : "#"
                },
            ]
        }
    }
};

</script>

<style lang="scss" scoped>
@import "../../assets/Style-scss/variables.scss";


.ms-container{
    margin: 0 auto;
    width: 30%;
    padding: 2rem;
}
</style>
