<template>
<div class="ms-card-item ">
  <div class="text-center text-white p-5">
    <h3>{{ food.title }}</h3>
    <h5 class="text-color-bay-leaf">{{ food.description }}</h5>
    <img
      :src="require(`../assets/images/${food.imgUrl}`)"
      class="card-img-top"
      alt=""
    />

    <button class="btn text-white bg-color-bay-leaf  rounded-pill btn-success">Shop  {{ food.title }} Food</button>
  </div>
  </div>
</template>

<script>
export default {
  props: {
    food: {
      type: Object,
      required: true,
    },
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/Style-scss/variables.scss";

.text-color-bay-leaf {
  color: #77ab82;
}
.bg-color-bay-leaf {
  color: #77ab82;
}

.ms-card-item{
     background-image: url('../assets/images/bg-transparent-3.png');
    background-color:#2a382a;
       :hover {
  transform: scale(1.1);
}}


</style>
