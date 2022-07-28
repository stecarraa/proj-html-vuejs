<template>
  <div class="container-fluid mt-5 ms-bg-heavy-metal">
    <div class="container">
      <div class="row align-items-center text-white p-5">
        <div class="col">
          <img
            class="w-75 mb-4"
            src="../assets/images/mobile-light-pet-logo-2x.png"
            alt=""
          />
          <p>
            1234 Avada Avenue Avadaville <br />
            info@yor-company.com <br />Call us : (1)234 5678
          </p>
        </div>

        <div class="col">
          <div class="">
            <h3>Shop By Brand</h3>
            <ul class="list-unstyled lh-lg">
              <li class="" v-for="(item, index) in brandItems" :key="index">
                <a class="text-decoration-none text-white" :href="item.url">{{
                  item.name
                }}</a>
              </li>
            </ul>
          </div>
        </div>

        <div class="col">
          <div class="">
            <h3>Useful Links</h3>
            <ul class="list-unstyled lh-lg">
              <li v-for="(item, index) in linkItems" :key="index">
                <a class="text-decoration-none text-white" :href="item.url">{{
                  item.name
                }}</a>
              </li>
            </ul>
          </div>
        </div>

        <div class="col">
          <div class="ms-container-news-letter p-5 text-center mb-5">
            <h3>Subscribe to our news letter</h3>
            <input
              type="mail"
              placeholder="Insert your email..*"
              class="form-control rounded-pill mt-3"
            />
            <button class="btn btn-success w-100 rounded-pill d-block mt-5">
              Subscibe
            </button>
          </div>
        </div>
        <hr />
      </div>
      <div class="ms-container">
        <ul class="list-unstyled d-flex justify-content-between">
          <li v-for="(item, index) in navItems" :key="index">
            <a class="text-decoration-none text-secondary" :href="item.url">{{
              item.name
            }}</a>
          </li>
        </ul>

        <div
          class="text-center ms-container d-flex justify-content-around text-white p-4"
        >
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
    </div>
    <div class="col-12 bg-black text-center p-4 text-white">
      <div>
        © Copyright 2012 - 2020 | Avada Theme by ThemeFusion | all Rights Reserved | Powered by WordPress
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LowerHeader",
  data: function () {
    return {
      brandItems: [
        {
          name: "Bed",
          url: "#",
        },
        {
          name: "Food",
          url: "#",
        },
        {
          name: "Toys",
          url: "#",
        },
        {
          name: "Transport",
          url: "#",
        },
      ],

      linkItems: [
        {
          name: "My account",
          url: "#",
        },
        {
          name: "Orders",
          url: "#",
        },
        {
          name: "Checkout",
          url: "#",
        },
        {
          name: "Cart",
          url: "#",
        },
      ],

      navItems: [
        {
          name: "Home",
          url: "#",
        },
        {
          name: "About",
          url: "#",
        },
        {
          name: "Blog",
          url: "#",
        },
        {
          name: "Contacts",
          url: "#",
        },
        {
          name: "Shop",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/Style-scss/variables.scss";

.ms-container {
  margin: 0 auto;
  width: 45%;
  padding: 2rem;
}

.ms-bg-heavy-metal {
  background-color: $colorGreenKelp;
}

.ms-container-news-letter {
  background-image: url("../assets/images/bg-transparent-3.png");
  background-color: $colorHeavyMetal;
}
</style>
