<template>
  <section class="team-area section-padding40 fix">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-xl-7 col-lg-8">
          <div class="section-tittle text-center mb-55">
            <h2>Admin & Staff</h2>
          </div>
        </div>
      </div>
      <div class="team-active">
        <no-ssr>
          <carousel :nav="false" :items="3">
            <div v-for="m in team" :key="m.name" class="single-cat text-center">
              <div class="cat-icon">
                <img :src="m.pic" alt="">
              </div>
              <div class="cat-cap">
                <h5><a target="_blank" :href="m.fb">{{ m.name }}</a></h5>
                <p>{{ m.position }}</p>
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
    // eslint-disable-next-line
    carousel: typeof window !== 'undefined' ? () => import('vue-owl-carousel2') : ''
  },
  data () {
    return {
      team: [
        {
          name: 'Rebecca Ultiano',
          position: 'Directress',
          pic: '/img/pics/REBECCA ULTIANO.jpg',
          fb: 'https://www.facebook.com/rebecca.ultiano'
        },
        {
          name: 'Eunice Ultiano-Dandan',
          position: 'Principal',
          pic: '/img/pics/EUNICE U. DANDAN.jpg',
          fb: 'https://www.facebook.com/eunice.ultiano'
        },
        {
          name: 'Jerome Dandan',
          position: 'Administrative Officer',
          pic: '/img/pics/JEROME DANDAN.jpg',
          fb: 'https://www.facebook.com/jerome.dandan.5'
        },
        {
          name: 'Ree Anne Ultiano',
          position: 'Registrar',
          pic: '/img/pics/REE ANNE ULTIANO.jpg',
          fb: 'https://www.facebook.com/RAyhang2x'
        },
        {
          name: 'Eiugine Ultiano',
          position: 'Administrative Officer',
          pic: '/img/pics/EIUIGINE ULTIANO.jpg',
          fb: 'https://www.facebook.com/eugineu'
        },
        {
          name: 'Jennie Louise Lucena',
          position: 'Admin Staff',
          pic: '/img/pics/JENNIE LUCENA.jpg',
          fb: 'https://www.facebook.com/jennie.lucena.9'
        }
      ]
    }
  }
}
</script>

<style>

</style>
