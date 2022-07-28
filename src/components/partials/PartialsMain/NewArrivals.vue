<template>
  <div>
    <!-- container with IMG new arrivals -->
    <div class="container">
      <div class="row">
        <div class="col-12 position-relative">
          <img
            class=""
            src="../../../assets/images/banner-3-2x-scaled.jpg"
            alt=""
          />
          <div class="position-absolute top-50 start-50 translate-middle">
            <div class="row">
              <div class="col-12 text-center text-white">
                <h6 class="text-uppercase">find the best animal supplies</h6>
                <h1 class="">New Arrivals Weekly</h1>
                <button class="btn bg-white rounded-pill mt-5">
                  Learn more about us
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- container with best sellers -->
    <div class="container">
      <div class="row mt-5">
        <div class="col-12">
          <h6 class="text-color-bay-leaf">All-time best sellers</h6>
        </div>
      </div>

      <div class="row">
        <div class="col-12 d-flex justify-content-between">
          <h2>Items everyone loves</h2>
          <button class="btn btn-success rounded-pill">
            View all products
          </button>
        </div>
      </div>
<!-- container with new prop item -->
        <div class="container mt-5">
          <div class="row">
              <item class="col-3" v-for="(item, index) in items" :key="index"
        :item="item" 
        />
           
          </div>
        </div>
     
    </div>
  </div>
</template>

<script>
import item from "../../../components/CardItem.vue" 


export default {
  name: "NewArrivals",
  components:{
    item,
  },
   data: function () {
    return {
      items: [
        {
          title: "Transport cage",
          price: "$ 25.00",
          imgUrl: "product-21.jpg"
        },
        {
          title: "Dog leash",
          price: "$ 25.00",
          imgUrl: "product-11.jpg"
        },
        {
          title: "Animal transport cage",
          price: "$ 25.00",
          original:"$ 35.00",
          imgUrl: "product-16.jpg"
        },
        {
          title: "colorful cat leash",
          price: "$ 12.00",
          imgUrl: "product-20.jpg"
        },
        
      ],
    }}
  
};
</script>

<style lang="scss" scoped>
@import "../../../assets/Style-scss/variables.scss";

img {
  width: 100%;
  margin-top: 10rem;
}

.text-color-bay-leaf {
  color: #77ab82;
}


</style>

