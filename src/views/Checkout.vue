<template>
  <div>
    <Navbar />
    <div class="container">
      <div class="row justify-content-center mt-5">
        <div class="col text-center">
          <img class="" src="../assets/images/Checkout.png" width="300" />
          <h2><strong>Success !!!</strong></h2>
          <h4>Your order is being processed</h4>
          <router-link to="/">
          <button class="btn btn-dark">
            <b-icon-arrow-return-right></b-icon-arrow-return-right> Back
          </button>
          </router-link>
        </div>
      </div>

      <div class="row">
        <div class="col"></div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Checkout",
  components: {
    Navbar,
  },
};
</script>

<style>
</style>