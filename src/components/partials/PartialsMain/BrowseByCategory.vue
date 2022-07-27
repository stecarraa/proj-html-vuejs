<template>
  <div>
    <!-- container with title -->
    <div class="container">
      <div class="row">
        <div class="col text-center">
          <h1>Browse By Category</h1>
          <p class="w-50 text-center m-auto mb-5 mt-2">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
            magni adipisci quo ullam! Sint nam eum voluptatum repellat tempore
            architect!
          </p>
        </div>
      </div>
    </div>
    <!-- container with object-card -->
    <div class="container">
      <div class="row">
        <div class="col d-flex">
          <div>
            <div class="m-1 text-center">
              <img
                src="../../../assets/images/product-9.jpg"
                class="card-img-top"
                alt=""
              />
              <div>
                <p class="card-text mt-3">Bed (1)</p>
              </div>
            </div>
          </div>
          <div>
            <div class="m-1 text-center">
              <img
                src="../../../assets/images/product-3.jpg"
                class="card-img-top"
                alt=""
              />
              <div>
                <p class="card-text mt-3">Food (6)</p>
              </div>
            </div>
          </div>
          <div>
            <div class="m-1 text-center">
              <img
                src="../../../assets/images/product-2.jpg"
                class="card-img-top"
                alt=""
              />
              <div>
                <p class="card-text mt-3">Toys (6)</p>
              </div>
            </div>
          </div>
          <div>
            <div class="m-1 text-center">
              <img
                src="../../../assets/images/product-4.jpg"
                class="card-img-top"
                alt=""
              />
              <div>
                <p class="card-text mt-3">Transport (6)</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- container with food-type-card -->

    <div class="container mt-5">
      <div class="row">
        <div class="col d-flex">
          <div class="ms-card m-1 text-center">
            <div class="card-body">
              <h2 class="card-title text-white">Kibble</h2>

              <h5 class="mt-3 ms-color-leaf  mb-4">Dry dog food</h5>

              <div class="card-text">
               <img src="../../../assets/images/food-transparent-16.png" alt="">
              </div>
              <a href="#" class="btn ms-bg-color-leaf rounded-pill text-white" @click.prevent="">Shop dry food</a>
            </div>
          </div>
          <div class="ms-card m-1 text-center">
            <div class="card-body">
              <h2 class="card-title text-white">Moist</h2>

              <h5 class="mt-3 ms-color-leaf  mb-4">Canned dog food</h5>
              <div class="card-text">
               <img src="../../../assets/images/food-transparent-17.png" alt="">
              </div>
              <a href="#" class="btn ms-bg-color-leaf rounded-pill text-white" @click.prevent="">Shop moist food</a>
            </div>
          </div>
          <div class="ms-card m-1 text-center">
            <div class="card-body">
              <h2 class="card-title text-white">Frozen</h2>

              <h5 class="mt-3 ms-color-leaf  mb-4">Freeze-dried dog food</h5>
              <div class="card-text">
               <img src="../../../assets/images/food-transparent-18.png" alt="">
              </div>
              <a href="#" class="btn ms-bg-color-leaf rounded-pill text-white" @click.prevent="">Shop frozen food</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BrowseByCategory",
};
</script>

<style lang="scss" scoped>
@import "../../../assets/Style-scss/variables.scss";

.ms-card{
    background-image: url('../../../assets/images/bg-transparent-3.png');
    background-color: $colorHeavyMetal;
    padding: 4rem;
   
}
 .ms-bg-color-leaf{
        background-color: $colorBayLeaf;

    }
.ms-color-leaf{
        color: $colorBayLeaf;

    }

.card-text{
    img{
        width: 100%;
    }
}

</style>
