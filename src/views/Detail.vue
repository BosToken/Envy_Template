<template>
  <div>
    <Navbar />
    <div class="container">
      <div class="row mt-3">
        <div class="col">
          <nav aria-label="breadcrumb">
            <ol class="breadcrumb">
              <li class="breadcrumb-item">
                <router-link to="/" class="text-dark">Home</router-link>
              </li>
              <li class="breadcrumb-item">
                <router-link to="/product" class="text-dark"
                  >Product</router-link
                >
              </li>
              <li class="breadcrumb-item">
                <router-link to="/detail" class="text-dark">Detail</router-link>
              </li>
            </ol>
          </nav>
        </div>
      </div>

      <div class="row">
        <div class="col-md-6">
          <img
            src="../assets/product/bajutidur.jpg"
            class="img-fluid shadow"
            alt="..."
          />
        </div>
        <div class="col-md-6">
          <h2><strong>Baju Tidur</strong></h2>
          <hr />
          <h4>Price : RP. <strong>105.000</strong></h4>
          <form>
            <div class="mb-3">
              <label for="value">Value</label>
              <input type="number" class="form-control" />
            </div>
            <div class="mb-3">
              <label for="value">Note</label>
              <textarea class="form-control" placeholder="Note..."></textarea>
            </div>
            <button type="submit" class="btn btn-success">
              <b-icon-plus></b-icon-plus> Add To Cart
            </button>
            <br /><br />
            <button type="submit" class="btn btn-dark">
              <b-icon-cart></b-icon-cart> Buy
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Detail",
  components: {
    Navbar,
  },
};
</script>

<style>
</style>