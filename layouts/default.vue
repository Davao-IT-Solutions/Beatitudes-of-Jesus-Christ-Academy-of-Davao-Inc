<template>
  <div>
    <Header />
    <transition name="fade">
      <Nuxt />
    </transition>
    <Footer />
  </div>
</template>

<style>
/* Enter and leave animations can use different */
/* durations and timing functions.              */
.slide-fade-enter-active {
  transition: all 0.5s ease;
}
.slide-fade-leave-active {
  transition: all 0.5s cubic-bezier(1.0, 0.5, 0.5, 1.0);
}
.slide-fade-enter {
  transform: translateY(10px);
  opacity: 0;
}
.slide-fade-leave-to {
  transform: translateY(10px);
  opacity: 0;
}

.fade-enter-active, .fade-leave-active {
  transition: opacity .5s
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0
}
</style>
