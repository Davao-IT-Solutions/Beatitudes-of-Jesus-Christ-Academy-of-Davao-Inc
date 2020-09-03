<template>
  <section class="team-area section-padding40 fix">
    <div class="container">
      <div class="team-active">
        <div class="row">
          <div v-for="teacher in teachers" :key="teacher.name" class="col-md-4">
            <div class="single-cat text-center mb-5">
              <div class="cat-icon">
                <img :src="teacher.image" alt="" class="img-fluid">
              </div>
              <div class="cat-cap">
                <h5><a target="_blank" :href="teacher.fb">{{ teacher.name }}</a></h5>
                <p>{{ teacher.subject }}</p>
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
      teachers: [
        {
          name: 'Danmerlou Galindo',
          subject: 'Prekinder & Kindergarten',
          image: '/img/pics/TEACHER DAN.jpg',
          fb: 'https://www.facebook.com/teach.dan.31'
        },
        {
          name: 'Jaryl Lucena',
          subject: 'Nursery & Kindergarten',
          image: '/img/pics/TEACHER JAJA.jpg',
          fb: 'https://www.facebook.com/teachers.jaryl.3'
        },
        {
          name: 'Bernardine Tan',
          subject: 'Grade 6',
          image: '/img/pics/TEACHER BERN.jpg',
          fb: 'https://www.facebook.com/bernardine.tan.16'
        },
        {
          name: 'Mary Joy Bentulan',
          subject: 'Grade 6',
          image: '/img/pics/TEACHER JOY.jpg',
          fb: 'https://www.facebook.com/joy.mjbentulan'
        },
        {
          name: 'Ryan Corella',
          subject: 'Grade 5',
          image: '/img/pics/TEACHER RYAN.jpg',
          fb: 'https://www.facebook.com/ryan.corella.54'
        },
        {
          name: 'Cheryl Canillo',
          subject: 'Grade 5',
          image: '/img/pics/TEACHER CHERYL.jpg',
          fb: 'https://www.facebook.com/teach.cheryl'
        },
        {
          name: 'Wilson Quidet',
          subject: 'Grade 4',
          image: '/img/pics/TEACHER WILSON.jpg',
          fb: 'https://www.facebook.com/teachwilson.quidet'
        },
        {
          name: 'Liezyl Descallar',
          subject: 'Grade 4',
          image: '/img/pics/TEACHER LIEZYL.jpg',
          fb: 'https://www.facebook.com/nikka.zhane.7'
        },
        {
          name: 'Julyka Grace Flores',
          subject: 'Grade 3',
          image: '/img/pics/TEACHER LYKA.jpg',
          fb: 'https://www.facebook.com/teach.lyka'
        },
        {
          name: 'Marlou Jade Alivio',
          subject: 'Grade 3',
          image: '/img/pics/TEACHER JADE.jpg',
          fb: 'https://www.facebook.com/jade.alivio.3762'
        },
        {
          name: 'Jaynnie Allyza Vigonte',
          subject: 'Grade 2',
          image: '/img/pics/TEACHER JAYNNIE.jpg',
          fb: 'https://www.facebook.com/teachjayn.vigonte'
        },
        {
          name: 'Rica Mae Jubac',
          subject: 'Grade 2',
          image: '/img/pics/TEACHER RICA.jpg',
          fb: 'https://www.facebook.com/rica.jubac'
        },
        {
          name: 'Josephine Mediano',
          subject: 'Grade 1',
          image: '/img/pics/TEACHER JO.jpg',
          fb: 'https://www.facebook.com/josephine.mediano'
        },
        {
          name: 'Elvie Manlanat',
          subject: 'Grade 1',
          image: '/img/pics/TEACHER ELVIE.jpg',
          fb: 'https://www.facebook.com/elvieghee.manlanat'
        }
      ]
    }
  }
}
</script>

<style>

</style>
