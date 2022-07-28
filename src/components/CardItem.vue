<template>
   <div class="card-item">
                <div class="m-1 text-center">
                  <img 
                    :src="require(`../assets/images/${item.imgUrl}`)"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <p class="mt-3">{{ item.title }}</p>
                    <p class="mt-3 text-color-bay-leaf"><span class="text-decoration-line-through ">{{item.original}}</span>{{item.price}}</p>
                  </div>
                </div>
              </div>
</template>

<script>
export default {

     props: {
        item: {
            type: Object,
            required: true,
        }
    }

}
</script>

<style lang="scss" scoped>
@import "../assets/Style-scss/variables.scss";


.text-color-bay-leaf{
  color: #77ab82;

}


</style>