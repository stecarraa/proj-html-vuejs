<template>
  <div class="card-item text-center">
    <div class="m-1 position-relative text-center">
      <img
        :src="require(`../assets/images/${item.imgUrl}`)"
        class="card-img-top"
        alt=""
      />
      <div class="position-absolute top-50 start-50 translate-middle">
        <div class="text-white rounded-circle circle-bg text-hover">
          <i class="fa-solid fa-cart-shopping"></i>
        </div>
        <div class="text-center text-white text-hover">View cart</div>
      </div>
    </div>
    <div>
      <p class="mt-3">{{ item.title }}</p>
      <p class="mt-3 text-color-bay-leaf">
        <span class="text-decoration-line-through">{{ item.original }}</span
        >{{ item.price }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    item: {
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
.text-hover {
  display: none;
}

.card-item:hover .text-hover {
  display: block;
}

.circle-bg {
  background-color: black;
  opacity: 0.75;
  padding: 3rem;
}
</style>
