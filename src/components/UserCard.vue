<template>
   <div class="card-item">
                <div class="m-1 text-center">
                  <img 
                    :src="require(`../assets/images/${testimonial.userUrl}`)"
                    class="rounded-circle"
                    alt=""
                  />
                  <div>
                    <p class="mt-3 text-white">{{ testimonial.description }}</p>
                    <p class="mt-3 text-secondary">{{testimonial.name}}</p>
                  </div>
                </div>
              </div>
</template>

<script>
export default {

     props: {
        testimonial: {
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

img {
  height: 8rem;
  width: 8rem;
}


</style>