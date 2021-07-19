<template>
  <div class="hero">
    <!-- Desktop -->
    <body>
      <div class="d-none d-md-block">
        <div class="row mt-4">
          <div class="col-md-6">
            <div class="d-flex h-100">
              <div class="justify-content-center align-self-center">
                <h2><strong>Show up your,</strong><br /></h2>
                <h4>best style</h4>
                <router-link to="/product">
                  <button class="btn btn-lg btn-dark">
                    <b-icon-arrow-right></b-icon-arrow-right> More
                  </button>
                </router-link>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <img src="../assets/images/Left_Blog.png" width="100%" />
          </div>
        </div>
      </div>

      <!-- Mobile -->
      <div class="d-sm-block d-md-none">
        <div class="row mt-4">
          <div class="col-md-6">
            <img src="../assets/images/Left_Blog.png" width="100%" />
          </div>
          <div class="col-md-6">
            <div class="d-flex h-100">
              <div class="justify-content-center align-self-center">
                <h2><strong>Show up your,</strong><br />best style</h2>
                <button class="btn btn-lg btn-dark">
                  <b-icon-arrow-return-right></b-icon-arrow-return-right> See
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </body>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>