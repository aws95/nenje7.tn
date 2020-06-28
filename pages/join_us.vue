<template>
  <div>
    <div class="contact-page-wrap">
      <div class="container">
        <div class="row">
          <div class="col-12 col-lg-12">
            <div class="entry-content">
              <h2>Meet a mentor</h2>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris. Lorem ipsum dolor sit amet, conse ctetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tempus vestib ulum mauris quis aliquam. Integer accu msan sodales odio, id tempus velit ullamc.</p>
            </div>
          </div>
          <!-- .col -->

          <div class="col-12 col-lg-12">
            <form class="contact-form">
              <input type="text" placeholder="Full Name" />
              <input type="email" placeholder="Email" />
              <input type="text" placeholder="Phone" />
              <label>Date of Birth :</label>
              <input class="mb-3" type="date" placeholder="Date of Birth" />
              <br />
              <label>Professional Status :</label>
              <div class="form-check form-check-inline">
                <input
                  class="form-check-input"
                  type="radio"
                  name="inlineRadioOptions"
                  id="inlineRadio1"
                  value="student"
                />
                <label class="form-check-label" for="inlineRadio1">Student</label>
              </div>
              <div class="form-check form-check-inline">
                <input
                  class="form-check-input"
                  type="radio"
                  name="inlineRadioOptions"
                  id="inlineRadio2"
                  value="mentor"
                />
                <label class="form-check-label" for="inlineRadio2">Mentor</label>
              </div>
              <input type="text" placeholder="School" />
              <input type="text" placeholder="Filed of studies" />
              <input type="text" placeholder="Year" />
              <input type="text" placeholder="Mentorship filed" />
              <input type="text" placeholder="Profession" />
              <input type="text" placeholder="Years of experience" />
              <input type="text" placeholder="Availability (days of week)" />

              <span>
                <input class="btn gradient-bg" type="submit" value="Submit" />
              </span>
            </form>
            <!-- .contact-form -->
          </div>
        </div>
        <!-- .row -->
      </div>
      <!-- .container -->
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>