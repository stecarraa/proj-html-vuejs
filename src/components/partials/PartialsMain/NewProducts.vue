<template>
  <div>
    <div class="container">
        <div class="row text-center mt-5">
            <div class="col-12">
                <h1>New products arrival</h1>
                <h5>Latest products</h5>
            </div>
        </div>
        <div class="row">
<item class="col-4" v-for="(item, index) in items" :key="index"
        :item="item" 
        />
              
          </div>
        </div>
    </div>
  
</template>

<script>
import item from "../../../components/CardItem.vue"

export default {
name:'NewProducts',
components:{
    item,
  },
  data: function () {
    return {
      items: [
        {
          title: "Colored ped bed",
          price: "$ 18.00 - $ 26.00",
          imgUrl: "product-8.jpg"
        },
        {
          title: "Colorful ball set",
          price: "$ 29.00",
          imgUrl: "product-2.jpg"
        },
        {
          title: "Dog bone",
          price: "$ 18.00",
          original:"$ 29.00",
          imgUrl: "product-3.jpg"
        },
        {
          title: "Animal transport bag",
          price: "$ 29.00",
          imgUrl: "product-4.jpg"
        },
         {
          title: "Animal transport cage",
          price: "$ 35.00",
          imgUrl: "product-5.jpg"
        },
        {
          title: "Closable cat litter",
          price: "$ 16.00",
          imgUrl: "product-10.jpg"
        },
        
      ],
    }}
  
}
</script>

<style lang="scss" scoped>

</style>