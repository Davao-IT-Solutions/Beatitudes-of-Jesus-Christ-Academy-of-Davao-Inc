<template>
  <section class="team-area section-padding40 fix">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-xl-7 col-lg-8">
          <div class="section-tittle text-center mb-55">
            <h2>Our Teachers</h2>
          </div>
        </div>
      </div>
      <div class="team-active">
        <no-ssr>
          <carousel :nav="false" :items="4">
            <div class="single-cat text-center">
              <div class="cat-icon">
                <img src="/img/gallery/team1.png" alt="">
              </div>
              <div class="cat-cap">
                <h5><a href="services.html">Mr. Urela</a></h5>
                <p>The automated process all your website tasks.</p>
              </div>
            </div>
            <div class="single-cat text-center">
              <div class="cat-icon">
                <img src="/img/gallery/team2.png" alt="">
              </div>
              <div class="cat-cap">
                <h5><a href="services.html">Mr. Uttom</a></h5>
                <p>The automated process all your website tasks.</p>
              </div>
            </div>
            <div class="single-cat text-center">
              <div class="cat-icon">
                <img src="/img/gallery/team3.png" alt="">
              </div>
              <div class="cat-cap">
                <h5><a href="services.html">Mr. Shakil</a></h5>
                <p>The automated process all your website tasks.</p>
              </div>
            </div>
            <div class="single-cat text-center">
              <div class="cat-icon">
                <img src="/img/gallery/team4.png" alt="">
              </div>
              <div class="cat-cap">
                <h5><a href="services.html">Mr. Arafat</a></h5>
                <p>The automated process all your website tasks.</p>
              </div>
            </div>
            <div class="single-cat text-center">
              <div class="cat-icon">
                <img src="/img/gallery/team3.png" alt="">
              </div>
              <div class="cat-cap">
                <h5><a href="services.html">Mr. saiful</a></h5>
                <p>The automated process all your website tasks.</p>
              </div>
            </div>
          </carousel>
        </no-ssr>
      </div>
      <div class="row justify-content-center">
        <div class="col-xl-12">
          <div class="section-tittle text-center mt-20">
            <nuxt-link to="/our-teachers" class="border-btn">
              View All Teachers
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  components: {
    // eslint-disable-next-line
    carousel: typeof window !== 'undefined' ? () => import('vue-owl-carousel2') : ''
  }
}
</script>

<style>

</style>
