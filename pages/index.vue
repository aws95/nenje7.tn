<template>
  <div>
    <div>
      <!-- .hero-slider -->
      <div class="home-page-icon-boxes">
        <div class="container">
          <p
            class="text-center"
          >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris quis aliquam.</p>
          <div class="row">
            <div class="col-12 col-md-6 col-lg-4 mt-4 mt-lg-0">
              <div class="icon-box">
                <header class="entry-header">
                  <h3 class="entry-title">Vision statement</h3>
                </header>

                <div class="entry-content">
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris quis aliquam.</p>
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6 col-lg-4 mt-4 mt-lg-0">
              <div class="icon-box">
                <header class="entry-header">
                  <h3 class="entry-title">Vision statement</h3>
                </header>

                <div class="entry-content">
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris quis aliquam.</p>
                </div>
              </div>
            </div>

            <div class="col-12 col-md-6 col-lg-4 mt-4 mt-lg-0">
              <div class="icon-box">
                <header class="entry-header">
                  <h3 class="entry-title">Vision statement</h3>
                </header>

                <div class="entry-content">
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris quis aliquam.</p>
                </div>
              </div>
            </div>
          </div>
          <!-- .row -->
        </div>
        <!-- .container -->
      </div>
      <!-- .home-page-icon-boxes -->
      <div class="home-page-limestone">
        <div class="container">
          <h1 class="text-center">Our Impact</h1>
          <div class="row align-items-end">
            <div class="coL-12 col-lg-6">
              <div class="section-heading">
                <h2
                  class="entry-title"
                >Dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris quis aliquam. Lorem ipsum dolor sit amet.</h2>

                <p
                  class="mt-5"
                >Dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris quis aliquam. Lorem ipsum dolor sit amet.</p>
              </div>
              <!-- .section-heading -->
            </div>
            <!-- .col -->

            <div class="col-12 col-lg-6">
              <div class="milestones d-flex flex-wrap justify-content-between">
                <div class="col-6 col-sm-4 mt-5 mt-lg-0 text-center">
                  <div class="counter-box">
                    <div class="d-flex justify-content-center align-items-center">
                      <img src="../assets/images/student.png" alt />
                    </div>
                    <div class="d-flex justify-content-center align-items-baseline">
                      <div class="start-counter" data-to="24" data-speed="2000"></div>
                      <div class="counter-Students">Students</div>
                    </div>
                  </div>
                  <!-- counter-box -->
                </div>
                <div class="col-6 col-sm-4 mt-5 mt-lg-0 text-center">
                  <div class="counter-box">
                    <div class="d-flex justify-content-center align-items-center">
                      <img src="../assets/images/mentor.png" alt />
                    </div>
                    <div class="d-flex justify-content-center align-items-baseline">
                      <div class="start-counter" data-to="8" data-speed="2000"></div>
                      <div class="counter-Mentors">Mentors</div>
                    </div>
                  </div>
                  <!-- counter-box -->
                </div>
                <!-- .col -->
              </div>
              <!-- .milestones -->
            </div>
            <!-- .col -->
          </div>
          <!-- .row -->
        </div>
        <!-- .container -->
      </div>
      <!-- .home-page-limestone -->
      <div class="our-parteners">
        <div class="container">
          <h1 class="text-center">Our Partners</h1>
          <Slider />
          <div class="mt-5 container text-center">
            <a href="/" class="btn gradient-bg mr-2">Partner with us</a>
          </div>
          <!-- .row -->
        </div>
        <!-- .container -->
      </div>
      <!-- .our-parteners -->
    </div>
  </div>
</template>

<script>
import Slider from "~/components/Slider";
export default {
  composnents: {
    Slider
  }
};
</script>

