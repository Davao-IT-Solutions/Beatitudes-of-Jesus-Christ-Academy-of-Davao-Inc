<template>
  <section class="team-area section-padding40 fix">
    <div class="container">
      <div class="team-active">
        <div class="row">
          <div v-for="teacher in teachers" :key="teacher" class="col-md-3">
            <div class="single-cat text-center">
              <div class="cat-icon">
                <img :src="teacher.image" alt="">
              </div>
              <div class="cat-cap">
                <h5><a href="#">{{ teacher.name }}</a></h5>
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
          name: 'Mr. Urela',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team1.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team2.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team3.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team4.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team1.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team2.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team3.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team4.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team4.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team1.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team3.png'
        },
        {
          name: 'Mr. Urela2',
          subject: 'Subject 1, Subject 2, Subject 3',
          image: '/img/gallery/team2.png'
        }
      ]
    }
  }
}
</script>

<style>

</style>
