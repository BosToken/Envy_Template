<template>
  <div>
    <Navbar />
    <div class="container">
      <Hero />

      <div class="row mt-4">
        <div class="col">
          <h2>
            <strong>Choose Design</strong>
          </h2>
        </div>
      </div>

      <div class="row mb-3">
        <div class="col-md-3 mt-4">
          <div class="card">
            <img src="../assets/design/beast.png" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>The Beast</h5>
                <p>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <a href="" class="btn btn-dark">
                  <b-icon-eye></b-icon-eye>
                  See
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-4">
          <div class="card">
            <img src="../assets/design/redliquid.png" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>RED LIQUID</h5>
                <p>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <a href="" class="btn btn-dark">
                  <b-icon-eye></b-icon-eye>
                  See
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-4">
          <div class="card">
            <img src="../assets/design/blackjoke.png" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>BLACK JOKE</h5>
                <p>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <a href="" class="btn btn-dark">
                  <b-icon-eye></b-icon-eye>
                  See
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-3 mt-4">
          <div class="card">
            <img src="../assets/design/heretic.png" alt="" />
            <div class="card-body">
              <div class="card-title">
                <h5>HERETIC</h5>
                <p>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <a href="" class="btn btn-dark">
                  <b-icon-eye></b-icon-eye>
                  See
                </a>
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
import Hero from "@/components/Hero.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Hero,
  },
};
</script>
