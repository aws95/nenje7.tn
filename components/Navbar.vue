<template>
  <div>
    <header class="site-header">
      <div class="nav-bar">
        <div class="container">
          <div class="row">
            <div class="col-12 d-flex justify-content-between align-items-center">
              <div class="site-branding align-items-center">
                <a class="d-block">
                  <nuxt-link to="/">
                    <img class="d-block logo-nenje7" src="../assets/images/logo.png" alt="logo" />
                  </nuxt-link>
                </a>
              </div>
              <!-- .site-branding -->

              <nav class="site-navigation d-flex justify-content-end align-items-center">
                <ul
                  class="d-flex flex-column flex-lg-row justify-content-lg-end align-content-center"
                >
                  <li>
                    <nuxt-link to="/">Home</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/about_us">About us</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/comming_soon">Academic</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/comming_soon">Opportunities</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/meet_a_mentor">Meet a Mentor</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/comming_soon">Blog</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/join_us">Join us</nuxt-link>
                  </li>
                </ul>
              </nav>
              <!-- .site-navigation -->

              <div class="hamburger-menu d-lg-none">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
              </div>
              <!-- .hamburger-menu -->
            </div>
            <!-- .col -->
          </div>
          <!-- .row -->
        </div>
        <!-- .container -->
      </div>
      <!-- .nav-bar -->
    </header>
  </div>
</template>

<script>
export default {
 
};
</script>

<style lang="scss" scoped>
</style>