<template>
  <div>
    <div class="container ms-margin-top">
        <div class="row text-center">
            <div class="col-12">
                <h1>Get the best tips & tricks</h1>
                <h4>recent articles</h4>
            </div>
        </div>
        <div class="row">
          <div class="row">
            <div class="col d-flex">
              <div>
                <div class="m-3 text-center">
                  <img
                    src="../../../assets/images/blog-1.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <h4 class="card-text mt-3">How to 'loose leash walk' your dog</h4>
                    <p class="card-text mt-3">April 21st, 2020</p>
                  </div>
                </div>
              </div>
              <div>
                <div class="m-3 text-center">
                  <img
                    src="../../../assets/images/blog-2.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <h4 class="card-text mt-3">Stop cats from scratching furniture</h4>
                    <p class="card-text mt-3">April 19th, 2020</p>
                  </div>
                </div>
              </div>
              <div>
                <div class="m-3 text-center">
                  <img
                    src="../../../assets/images/blog-3.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <h4 class="card-text mt-3">Where to buy best pet food</h4>
                    <p class="card-text mt-3">April 18th, 2020</p>
                  </div>
                </div>
              </div>
              <div>
                <div class="m-3 text-center">
                  <img
                    src="../../../assets/images/blog-4.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <h4 class="card-text mt-3">Proper care for your pet toys</h4>
                    <p class="card-text mt-3">April 17th, 2020</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row text-center">
          <div class="col-12">
            <button class="btn mt-3 mb-5 rounded-pill btn-success">Read all articles</button>
          </div>
        </div>
    </div>
    <div class="ms-container">
      <div class="d-flex">
        <div class="col position-relative">
            <img class="" src="../../../assets/images/banner-8-2x.jpg" alt="">
            <div class="position-absolute top-50 start-50 translate-middle text-white text-center">
              <h6 class="text-uppercase mb-4">find the best animal supplies</h6>
              <h1 class="mb-5">Popular accessories</h1>
              <button class="btn rounded-pill btn-light">View all toys accessories</button>
            </div>
        </div>

        <div class="col position-relative">
            <img src="../../../assets/images/banner-9-2x.jpg" alt="">
             <div class="position-absolute top-50 start-50 translate-middle text-white text-center">
              <h6 class="text-uppercase mb-4">find the best food</h6>
              <h1 class="mb-5">New food arrival</h1>
              <button class="btn rounded-pill btn-light">View all food product</button>
            </div>
        </div>
      </div>
    </div>
    <div class="ms-container-paw">
     <div class="container">
       <div class="row p-5 text-white text-center">
        <div class="col ">
          <div class=""><i class="fa-solid fa-truck"></i></div>
          Free worldwide deliveries
        </div>
         <div class="col">
          <div class=""><i class="fa-regular fa-map"></i></div>
          Free stores near you
        </div>
         <div class="col">
          <div class=""><i class="fa-solid fa-dollar-sign"></i></div>
          Best price guarranteed
        </div>
         <div class="col">
          <div class=""><i class="fa-regular fa-credit-card"></i></div>
          All credit card accepted
        </div>
      </div>
     </div>
    </div>
  </div>
</template>

<script>
export default {
    name:'TipsTricks'

}
</script>

<style lang="scss" scoped>
@import "../../../assets/Style-scss/variables.scss";

.ms-margin-top{
  margin-top: 20rem;
}

img{
  width: 100%;
}
.ms-container-paw {
   background-image: url("../../../assets/images/bg-transparent-3.png");
  background-color: $colorHeavyMetal;
  padding: 4rem;
  
}
 i{
  font-size: 3rem;
  padding: 2rem;
 }
</style>