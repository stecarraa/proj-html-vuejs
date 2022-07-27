<template>
  <div class="ms-container-fluid">
        <div class="row">
          <div class="container w-75">
              <div class="col-12 d-flex justify-content-between p-3">
                <div class="col-4 text-white">
                    international shipping services
                </div>
                 <div class="col-4 text-white">
                   see our store hours and services
                </div>
                 <div class="col-4 text-white">
                    we prise the best match to give you the best deals
                </div>
            </div>
        </div>
          </div>
        <div class="row">
            <div class="col-12">
                <img class="opacity-75 position-relative" src="../../assets/images/banner-5-2x-scaled.jpg" alt="">
                <div class="container  jumbo-text">
                    <div class="row">
                        <div class="col text-white">
                            <h6 class="text-uppercase mb-4">Find the best animal supplies</h6>
                            <h1>We know animals are a part of your family, let us help take care of them</h1>
                            <button class="btn bg-white rounded-pill  mt-5">Learn more about us</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row ">
            <div class="col-12 d-flex align-items-center text-center mt-4">
                <div class="col-4">
                    <img class="w-50" src="../../assets/images/food-transparent-5.png" alt="">
                </div>
                <div class="col-4 text-white">
                Get 25$ OFF your first purchase of our homemade pet food
                </div>
                 <div class="col-4">
                    <a class="text-secondary" href="#">Visit the shop</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "MyJumbotron",
 
};

</script>

<style lang="scss" scoped>
@import "../../assets/Style-scss/variables.scss";


.ms-container-fluid{
    background-image: url('../..//assets/images/bg-transparent-3.png');
    background-color: $colorHeavyMetal;
img{
    height: 100%;
    width: 100%;
}
}

.jumbo-text{
    position: absolute;
    top:25rem;
    left: 15rem;
    display: block;
    width: 35%;

}

</style>
