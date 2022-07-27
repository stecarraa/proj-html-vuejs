<template>
  <div>
    <!-- container with IMG new arrivals -->
    <div class="container">
      <div class="row">
        <div class="col-12 position-relative">
          <img
            class=""
            src="../../../assets/images/banner-3-2x-scaled.jpg"
            alt=""
          />
          <div class="position-absolute top-50 start-50 translate-middle">
            <div class="row">
              <div class="col-12 text-center text-white">
                <h6 class="text-uppercase">find the best animal supplies</h6>
                <h1 class="">New Arrivals Weekly</h1>
                <button class="btn bg-white rounded-pill mt-5">
                  Learn more about us
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- container with best sellers -->
    <div class="container">
      <div class="row mt-5">
        <div class="col-12">
          <h6>All-time best sellers</h6>
        </div>
      </div>

      <div class="row">
        <div class="col-12 d-flex justify-content-between">
          <h2>Items everyone loves</h2>
          <button class="btn btn-success rounded-pill">
            View all products
          </button>
        </div>
      </div>

      <div class="row">
        <div class="container">
          <div class="row">
            <div class="col d-flex">
              <div>
                <div class="m-1 text-center">
                  <img
                    src="../../../assets/images/product-21.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <p class="card-text mt-3">Transport cage</p>
                    <p class="card-text mt-3">$25.00</p>
                  </div>
                </div>
              </div>
              <div>
                <div class="m-1 text-center">
                  <img
                    src="../../../assets/images/product-11.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <p class="card-text mt-3">Dog leash</p>
                    <p class="card-text mt-3">$25.00</p>
                  </div>
                </div>
              </div>
              <div>
                <div class="m-1 text-center">
                  <img
                    src="../../../assets/images/product-5.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <p class="card-text mt-3">Animal transport cage</p>
                    <p class="card-text mt-3"><span class="text-decoration-line-through ">$35.00</span>$25.00</p>
                  </div>
                </div>
              </div>
              <div>
                <div class="m-1 text-center">
                  <img
                    src="../../../assets/images/product-20.jpg"
                    class="card-img-top"
                    alt=""
                  />
                  <div>
                    <p class="card-text mt-3">Colorful cat leash</p>
                    <p class="card-text mt-3">$12.00</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewArrivals",
};
</script>

<style lang="scss" scoped>
@import "../../../assets/Style-scss/variables.scss";

img {
  width: 100%;
  margin-top: 10rem;
}


</style>
>
