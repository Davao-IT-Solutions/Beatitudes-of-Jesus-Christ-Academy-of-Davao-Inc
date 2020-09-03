<template>
  <section class="team-area section-padding40 fix">
    <div class="container">
      <div class="team-active">
        <div class="row">
          <div v-for="admin in admins" :key="admin.name" class="col-md-4">
            <div class="single-cat text-center mb-5">
              <div class="cat-icon">
                <img :src="admin.image" alt="" class="img-fluid">
              </div>
              <div class="cat-cap">
                <h5><a target="_blank" :href="admin.fb">{{ admin.name }}</a></h5>
                <p>{{ admin.position }}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data () {
    return {
      admins: [
        {
          name: 'Rebecca Ultiano',
          position: 'Directress',
          image: '/img/pics/REBECCA ULTIANO.jpg',
          fb: 'https://www.facebook.com/rebecca.ultiano'
        },
        {
          name: 'Eunice Ultiano-Dandan',
          position: 'Principal',
          image: '/img/pics/EUNICE U. DANDAN.jpg',
          fb: 'https://www.facebook.com/eunice.ultiano'
        },
        {
          name: 'Jerome Dandan',
          position: 'Administrative Officer',
          image: '/img/pics/JEROME DANDAN.jpg',
          fb: 'https://www.facebook.com/jerome.dandan.5'
        },
        {
          name: 'Ree Anne Ultiano',
          position: 'Registrar',
          image: '/img/pics/REE ANNE ULTIANO.jpg',
          fb: 'https://www.facebook.com/RAyhang2x'
        },
        {
          name: 'Eiugine Ultiano',
          position: 'Administrative Officer',
          image: '/img/pics/EIUIGINE ULTIANO.jpg',
          fb: 'https://www.facebook.com/eugineu'
        },
        {
          name: 'Jennie Louise Lucena',
          position: 'Admin Staff',
          image: '/img/pics/JENNIE LUCENA.jpg',
          fb: 'https://www.facebook.com/jennie.lucena.9'
        }

      ]
    }
  }
}
</script>

<style>

</style>
