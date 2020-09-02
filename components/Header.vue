<template>
  <header>
    <div class="header-area header-transparent">
      <div class="main-header">
        <div class="header-bottom header-sticky" :class="{'sticky-bar': stickyBar}">
          <div class="container-fluid">
            <div class="row align-items-center">
              <!-- Logo -->
              <div class="col-xl-2 col-lg-2">
                <div class="logo">
                  <nuxt-link to="/">
                    <img src="/img/logo/bjcad_logo2.png" alt>
                  </nuxt-link>
                </div>
              </div>
              <div class="col-xl-10 col-lg-10">
                <div class="menu-wrapper d-flex align-items-center justify-content-end">
                  <!-- Main-menu -->
                  <div class="main-menu d-none d-lg-block">
                    <nav>
                      <ul id="navigation">
                        <li>
                          <nuxt-link to="/">
                            Home
                          </nuxt-link>
                        </li>
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
                            Contact
                          </nuxt-link>
                        </li>
                        <!-- Button
                        <li class="button-header margin-left">
                          <a href="/enroll" class="btn">Enroll Now</a>
                        </li>
                        -->
                        <li class="button-header margin-left">
                          <a target="_blank" href="https://vsmart.vibalgroup.com/account/login" class="btn">My Classroom</a>
                        </li>
                      </ul>
                    </nav>
                  </div>
                </div>
              </div>
              <!-- Mobile Menu -->
              <div class="col-12">
                <div class="mobile_menu d-block d-lg-none" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data () {
    return {
      stickyBar: false
    }
  },
  mounted () {
    // eslint-disable-next-line
    window.addEventListener('scroll', this.handleScroll)
  },
  destroyed () {
    window.removeEventListener('scroll', this.handleScroll)
  },
  methods: {
    handleScroll (event) {
      // eslint-disable-next-line no-console
      if (window.scrollY > 200) {
        this.stickyBar = true
      } else {
        this.stickyBar = false
      }
    }
  }
}
</script>

<style>
</style>
