<template>
  <div>
    <div class="ms-container position-relative mt-5">
      <div class="container">
        <div class="row">
          <div class="col-12 text-center text-white">
            <h1>Users testimonials</h1>
          </div>
        </div>
<!-- container with the testimonials -->
        <div class="row p-1 text-center mt-5">
           <testimonial class="col-4" v-for="(testimonial, index) in testimonials" :key="index"
        :testimonial="testimonial" 
        />
        </div> 
      </div>

      <!-- container for the news letter section -->
      <div
        class="container position-absolute top-100 start-50 translate-middle">
        <div class="ms-container-news-letter">
            <div class="row w-50">
                <div class="col-12 mt-5 mb-3">
                    <h1>Join our newsletter</h1>
                </div>
                <div class="col-12 mb-5">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Qui magni voluptatibus doloribus sunt sapiente doloremque.
                </div>
                <div class="col-12 d-flex justify-content-between">
                    <input class="rounded-pill form-control w-75" placeholder="Insert you email..*" type="mail"> <button class="btn btn-success rounded-pill">Subscibe</button>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import testimonial from "../../../components/UserCard.vue"
export default {
  name: "TestimonialsNewsLetter",
   components:{
    testimonial,
  },
   data: function () {
    return {
      testimonials: [
        {
          name: "Lisa Smith, ThemeFusion",
          description: " Lorem ipsum dolor sit amet consectetur adipisicing elit Molestias possimus assumenda praesentium! Eligendi aspernatu accusamus debitis.",
          userUrl: "avatar-3.jpg"
        },
        {
          name: "Melissa Green, ThemeFusion",
          description: "Lorem ipsum dolor sit amet consectetur adipisicing elit Molestias possimus assumenda praesentium! Eligendi aspernatu accusamus debitis.",

          userUrl: "avatar-1.jpg"
        },
        {
          name: "Sam Lewis, ThemeFusion",
          description: "Lorem ipsum dolor sit amet consectetur adipisicing elit Molestias possimus assumenda praesentium! Eligendi aspernatu accusamus debitis.", 

          userUrl: "avatar-4.jpg"
        }, 
      ],
    }}
  
};
</script>

<style lang="scss" scoped>
@import "../../../assets/Style-scss/variables.scss";

.ms-container {
  background-image: url("../../../assets/images/bg-transparent-3.png");
  background-color: $colorHeavyMetal;
  padding: 4rem;
  height: 80vh;
}
.ms-container-news-letter {
  background-image: url("../../../assets/images/banner-7-2x-scaled.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-color: $colorHeavyMetal;
  padding: 4rem;
  height: 40vh;
}

img {
  height: 8rem;
  width: 8rem;
}
</style>
