<template>
  <footer>
    <div class="footer-wrappper footer-bg">
      <!-- Footer Start-->
      <div class="footer-area footer-padding">
        <div class="container">
          <div class="row justify-content-between">
            <div class="col-xl-4 col-lg-5 col-md-4 col-sm-6">
              <div class="single-footer-caption mb-50">
                <div class="single-footer-caption mb-30">
                  <!-- logo -->
                  <div class="footer-logo mb-25">
                    <nuxt-link to="/">
                      <img src="/img/logo/bjcad_logo2.png" alt="Beatitudes Logo" style="width: 90%;">
                    </nuxt-link>
                  </div>
                  <div class="footer-tittle">
                    <div class="footer-pera">
                      <p>A Christian Educational Institution offering quality Christian education.</p>
                    </div>
                  </div>
                  <!-- social -->
                  <div class="footer-social">
                    <a target="_blank" href="https://www.facebook.com/Beatitudes-of-Jesus-Christ-Academy-of-Davao-Inc-156870594835472/about/?ref=page_internal"><i class="fab fa-facebook-f" /></a>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6">
              <div class="single-footer-caption mb-50">
                <div class="footer-tittle">
                  <h4>Explore</h4>
                  <ul>
                    <li>
                      <nuxt-link to="/about">
                        About Us
                      </nuxt-link>
                    </li>
                    <li>
                      <nuxt-link to="/our-teachers">
                        Our Teachers
                      </nuxt-link>
                    </li>
                    <li>
                      <nuxt-link to="/contact">
                        Contact Us
                      </nuxt-link>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-xl-6 col-lg-5 col-md-4 col-sm-6">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d7918.309928519346!2d125.50035041826389!3d7.108033239169518!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xa655ce80b50f674c!2sBeatitudes%20Of%20Jesus%20Christ%20Academy%20Of%20Davao!5e0!3m2!1sen!2sph!4v1598544082850!5m2!1sen!2sph"
                width="100%"
                height="250"
                frameborder="0"
                style="border:0;"
                allowfullscreen=""
                aria-hidden="false"
                tabindex="0"
              />
            </div>
          </div>
        </div>
      </div>
      <!-- footer-bottom area -->
      <div class="footer-bottom-area">
        <div class="container">
          <div class="footer-border">
            <div class="row d-flex align-items-center">
              <div class="col-xl-12 ">
                <div class="footer-copy-right text-center">
                  <p>
                    <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
                    Copyright &copy; {{ currentYear }} All rights reserved <br>
                    Made with <i class="fa fa-heart" aria-hidden="true" /> by <a href="https://colorlib.com" target="_blank">Colorlib</a>
                    &middot; Developed by <a href="https://www.davao.me" target="_blank">Davao IT Solutions</a>
                    <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Footer End-->
    </div>
  </footer>
</template>

<script>
export default {
  data () {
    return {
      currentYear: new Date().getFullYear()
    }
  }
}
</script>

<style>

</style>
