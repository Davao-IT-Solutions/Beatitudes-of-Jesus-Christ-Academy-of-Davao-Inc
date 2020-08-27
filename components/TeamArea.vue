<template>
  <section class="team-area section-padding40 fix">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-xl-7 col-lg-8">
          <div class="section-tittle text-center mb-55">
            <h2>Community experts</h2>
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
    </div>
  </section>
</template>

<script>

export default {
  components: {
    carousel: typeof window !== 'undefined' ? () => import('vue-owl-carousel2') : ''
  }
}
</script>

<style>

</style>
