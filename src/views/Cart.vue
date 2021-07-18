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
                <router-link to="/detail" class="text-dark">Cart</router-link>
              </li>
            </ol>
          </nav>
        </div>
      </div>

      <div class="row">
        <div class="col">
          <h2>My <strong>Cart</strong></h2>
          <table class="table">
            <tbody>
              <tr>
                <th scope="row">1</th>
                <td>
                  <img
                    class="img-fluid shadow"
                    src="../assets/product/bajutidur.jpg"
                    width="250"
                  />
                </td>
                <td>
                  Name : <strong>Baju Tidur</strong> <br />
                  Price : RP. <strong>105.000</strong> <br />
                  Value : <strong>2</strong>
                </td>
                <td>
                  <router-link to="/detail" class="btn btn-dark">
                    <b-icon-eye></b-icon-eye>
                    Detail
                  </router-link>
                   <br>
                   <br>
                  <router-link to="/" class="btn btn-danger">
                    <b-icon-minus></b-icon-minus>
                    Remove
                  </router-link>
                </td>
              </tr>
              <tr>
                <th scope="row">2</th>
                <td>
                  <img
                    class="img-fluid shadow"
                    src="../assets/product/hoodie1.jpg"
                    width="250"
                  />
                </td>
                <td>
                  Name : <strong>Hoodie abu-abu</strong> <br />
                  Price : RP. <strong>175.000</strong> <br />
                  Value : <strong>1</strong>
                </td>
                <td>
                  <router-link to="/detail" class="btn btn-dark">
                    <b-icon-eye></b-icon-eye>
                    Detail
                  </router-link>
                   <br>
                   <br>
                  <router-link to="/" class="btn btn-danger">
                    <b-icon-minus></b-icon-minus>
                    Remove
                  </router-link>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Cart",
  components: {
    Navbar,
  },
};
</script>

<style>
</style>