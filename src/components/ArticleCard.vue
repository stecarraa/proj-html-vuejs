<template>
  <div class="card-item text-center">
    <div class="m-1 position-relative">
      <img
        :src="require(`../assets/images/${blog.imgUrl}`)"
        class="card-img-top"
        alt=""
      />
      <div class="  position-absolute top-50 start-50 translate-middle">
        <h4 class="text-white text-hover">{{ blog.title }}</h4>
        <h6 class="text-white text-hover">Tips & tricks</h6>
      </div>
    </div>
    <div>
      <h2 class="mt-3">{{ blog.title }}</h2>
      <p class="mt-3">{{ blog.date }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    blog: {
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

.text-hover{
  display: none;
}

.card-item:hover .text-hover{
 
    display: block;
  
}

</style>
