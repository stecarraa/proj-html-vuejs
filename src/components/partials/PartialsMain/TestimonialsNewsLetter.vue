<template>
  <div>
    <div class="ms-container position-relative mt-5">
      <div class="container">
        <div class="row">
          <div class="col-12 text-center text-white">
            <h1>Users testimonials</h1>
          </div>
        </div>

        <div class="row p-1 text-center">
          <div class="col-4 mt-5 text-white">
            <div>
              <img
                class="rounded-circle mb-3"
                src="../../../assets/images/avatar-3.jpg"
                alt=""
              />
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Molestias possimus assumenda praesentium! Eligendi aspernatur
                accusamus debitis.
              </p>
              <p class="text-secondary">Lisa Smith, ThemeFusion</p>
            </div>
          </div>
          <div class="col-4 mt-5 text-white">
            <div>
              <img
                class="rounded-circle mb-3"
                src="../../../assets/images/avatar-1.jpg"
                alt=""
              />
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Molestias possimus assumenda praesentium! Eligendi aspernatur
                accusamus debitis.
              </p>
              <p class="text-secondary">Melissa Green, ThemeFusion</p>
            </div>
          </div>
          <div class="col-4 mt-5 text-white">
            <div>
              <img
                class="rounded-circle mb-3"
                src="../../../assets/images/avatar-4.jpg"
                alt=""
              />
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Molestias possimus assumenda praesentium! Eligendi aspernatur
                accusamus debitis.
              </p>
              <p class="text-secondary">Sam Lewis, ThemeFusion</p>
            </div>
          </div>
        </div>
      </div>
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
export default {
  name: "TestimonialsNewsLetter",
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
