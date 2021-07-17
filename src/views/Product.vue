<template>
  <div>
    <Navbar />
    <div class="container">
      <div class="row mt-3">
        <div class="col">
          <nav aria-label="breadcrumb">
            <ol class="breadcrumb">
              <li class="breadcrumb-item"><router-link to="/" class="text-dark">Home</router-link></li>
              <li class="breadcrumb-item"><router-link to="/product" class="text-dark">Product</router-link></li>
            </ol>
          </nav>
          
          <h2>Product</h2>
        </div>
      </div>

      <div class="row mt-3">
        <div class="col">
          <div class="input-group mb-3">
            <input
              type="text"
              class="form-control"
              placeholder="Search..."
              aria-label="Search"
              aria-describedby="basic-addon1"
            />
            <div class="input-group-prepend">
                <span class="input-group-text" id="basic-addon1">
                  <b-icon-search></b-icon-search>
                </span>
            </div>
          </div>
        </div>
      </div>

      <div class="row mb-4">
        <div class="col-md-3 mt-4">
          <div class="card">
            <img
              class="card-img-top"
              src="../assets/product/bajutidur.jpg"
              alt=""
            />
            <div class="card-body">
              <div class="card-title">
                <h5>Baju Tidur</h5>
                <p>Price : RP. 105.000</p>
                <router-link to="/detail" class="btn btn-dark">
                  <b-icon-cart></b-icon-cart>
                  Buy
                </router-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-4">
          <div class="card">
            <img
              class="card-img-top"
              src="../assets/product/hoodie1.jpg"
              alt=""
            />
            <div class="card-body">
              <div class="card-title">
                <h5>Hoodie abu-abu</h5>
                <p>Price : RP. 175.000</p>
                <router-link to="" class="btn btn-dark">
                  <b-icon-cart></b-icon-cart>
                  Buy
                </router-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-4">
          <div class="card">
            <img
              class="card-img-top"
              src="../assets/product/hoodie2.jpg"
              alt=""
            />
            <div class="card-body">
              <div class="card-title">
                <h5>Hoodie hitam pria</h5>
                <p>Price : RP. 125.000</p>
                <router-link to="" class="btn btn-dark">
                  <b-icon-cart></b-icon-cart>
                  Buy
                </router-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-4">
          <div class="card">
            <img
              class="card-img-top"
              src="../assets/product/tshirt1.jpg"
              alt=""
            />
            <div class="card-body">
              <div class="card-title">
                <h5>Tshirt Hitam</h5>
                <p>Price : RP. 100.000</p>
                <router-link to="" class="btn btn-dark">
                  <b-icon-cart></b-icon-cart>
                  Buy
                </router-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-4">
          <div class="card">
            <img
              class="card-img-top"
              src="../assets/product/tshirt2.jpg"
              alt=""
            />
            <div class="card-body">
              <div class="card-title">
                <h5>Tshirt Wanita</h5>
                <p>Price : RP. 100.000</p>
                <router-link to="" class="btn btn-dark">
                  <b-icon-cart></b-icon-cart>
                  Buy
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Product",
  components: {
    Navbar,
  },
};
</script>

<style>
</style>