<template>
  <div>
    <!-- container with title -->
    <div class="container mt-5">
      <div class="row">
        <div class="col text-center">
          <h1>Browse By Category</h1>
          <p class="w-50 text-center m-auto mb-5 mt-2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
            magni adipisci quo ullam! Sint nam eum voluptatum repellat tempore
            architect!
          </p>
        </div>
      </div>
    </div>
    <!-- container with object-card -->
    <div class="container">
      <div class="row">
        <item class="col" v-for="(item, index) in items" :key="index"
        :item="item" 
        />
      </div>
    </div>

    <!-- container with food-type-card -->

    <div class="container mt-5">
      <div class="row ">
         <food class="col m-1" v-for="(food, index) in foods" :key="index"
        :food="food" 
        />
       
      </div>
    </div>
  </div>
</template>

<script>
import food from "../../../components/FoodCard.vue" 
import item from "../../../components/CardItem.vue"

export default {
  name: "BrowseByCategory",
  components:{
    food,
    item,
  },
   data: function () {
    return {
      foods: [
        {
          title: "Kibble",
          description:"Dry dog food",
          imgUrl: "food-transparent-18.png"
        },
        {
          title: "Moist",
          description:"Canned dog food",
          imgUrl: "food-transparent-16.png"
        },
        {
          title: "Frozen",
          description:"Freeze-Dried dog food",
          original:"$ 35.00",
          imgUrl: "food-transparent-17.png"
        },
       
      ],
      items: [
        {
          title: "Bed (1)",
          imgUrl: "product-9.jpg"
        },
        {
          title: "Food (6)",
          imgUrl: "product-3.jpg"
        },
        {
          title: "Toys (6)",
         
          imgUrl: "product-2.jpg"
        },
        {
          title: "Transport (6)",
          imgUrl: "product-4.jpg"
        },
        
      ],
    }}
};
</script>

<style lang="scss" scoped>
@import "../../../assets/Style-scss/variables.scss";

.ms-card{
    background-image: url('../../../assets/images/bg-transparent-3.png');
    background-color: $colorHeavyMetal;
    padding: 4rem;
     :hover {
  transform: scale(1.1); 
}
   
   
}
 .ms-bg-color-leaf{
        background-color: $colorBayLeaf;

    }
.ms-color-leaf{
        color: $colorBayLeaf;

    }

.card-text{
    img{
        width: 100%;
    }
}

</style>
