<template>
   <div class="card-item">
                <div class="m-1 text-center">
                  <img 
                    :src="require(`../assets/images/${blog.imgUrl}`)"
                    class="card-img-top"
                    alt=""
                  />

                  <div>
                    <h2 class="mt-3">{{ blog.title }}</h2>
                    <p class="mt-3 ">{{blog.date}}</p>
                  </div>
                </div>
              </div>
</template>

<script>
export default {

     props: {
        blog: {
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