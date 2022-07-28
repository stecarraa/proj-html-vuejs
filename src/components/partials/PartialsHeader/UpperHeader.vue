<template>
  <div class="container-fluid border-bottom">
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex align-items-center">
          <div class="col-3 d d-flex align-items-center">
            <img class="m-3" src="../../../assets/images/logo-symbol.png" alt="" />
            <div>Avada Pet Supplies</div>
          </div>
          <div class="col-3">
            <div class="input-group">
        
              <div class="form-outline">
                <input type="search" placeholder="Search.." class="form-control rounded-pill" />
              </div>
            </div>
          </div>
          <div class="col-3"><span class="fw-bold">Questions?</span> Contact us : 1.800.123.4567</div>
          <div class="col-3 text-center">
            <i class="fa-brands fa-shopify m-3"></i>
            <i class="fa-regular fa-user"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "UpperHeader",
};
</script>

<style lang="scss" scoped>
@import "../../../assets/Style-scss/variables.scss";

img {
  height: 40px;
}
</style>
