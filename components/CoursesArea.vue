<template>
  <div class="courses-area section-padding40 fix">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-xl-7 col-lg-8">
          <div class="section-tittle text-center mb-55">
            <h2>Our featured courses</h2>
          </div>
        </div>
      </div>
      <div class="courses-actives">
        <no-ssr>
          <carousel :nav="false" :items="3">
            <!-- Single -->
            <div class="properties pb-20">
              <div class="properties__card">
                <div class="properties__img overlay1">
                  <a href="#"><img src="/img/gallery/featured1.png" alt=""></a>
                </div>
                <div class="properties__caption">
                  <p>User Experience</p>
                  <h3><a href="#">Fundamental of UX for Application design</a></h3>
                  <p>
                    The automated process all your website tasks. Discover tools and techniques to engage effectively with vulnerable children and young people.
                  </p>
                  <div class="properties__footer d-flex justify-content-between align-items-center">
                    <div class="restaurant-name">
                      <div class="rating">
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star-half" />
                      </div>
                      <p><span>(4.5)</span> based on 120</p>
                    </div>
                    <div class="price">
                      <span>$135</span>
                    </div>
                  </div>
                  <a href="#" class="border-btn border-btn2">Find out more</a>
                </div>
              </div>
            </div>
            <!-- Single -->
            <!-- Single -->
            <div class="properties pb-20">
              <div class="properties__card">
                <div class="properties__img overlay1">
                  <a href="#"><img src="/img/gallery/featured2.png" alt=""></a>
                </div>
                <div class="properties__caption">
                  <p>User Experience</p>
                  <h3><a href="#">Fundamental of UX for Application design</a></h3>
                  <p>
                    The automated process all your website tasks. Discover tools and techniques to engage effectively with vulnerable children and young people.
                  </p>
                  <div class="properties__footer d-flex justify-content-between align-items-center">
                    <div class="restaurant-name">
                      <div class="rating">
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star-half" />
                      </div>
                      <p><span>(4.5)</span> based on 120</p>
                    </div>
                    <div class="price">
                      <span>$135</span>
                    </div>
                  </div>
                  <a href="#" class="border-btn border-btn2">Find out more</a>
                </div>
              </div>
            </div>
            <!-- Single -->
            <!-- Single -->
            <div class="properties pb-20">
              <div class="properties__card">
                <div class="properties__img overlay1">
                  <a href="#"><img src="/img/gallery/featured3.png" alt=""></a>
                </div>
                <div class="properties__caption">
                  <p>User Experience</p>
                  <h3><a href="#">Fundamental of UX for Application design</a></h3>
                  <p>
                    The automated process all your website tasks. Discover tools and techniques to engage effectively with vulnerable children and young people.
                  </p>
                  <div class="properties__footer d-flex justify-content-between align-items-center">
                    <div class="restaurant-name">
                      <div class="rating">
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star-half" />
                      </div>
                      <p><span>(4.5)</span> based on 120</p>
                    </div>
                    <div class="price">
                      <span>$135</span>
                    </div>
                  </div>
                  <a href="#" class="border-btn border-btn2">Find out more</a>
                </div>
              </div>
            </div>
            <!-- Single -->
            <!-- Single -->
            <div class="properties pb-20">
              <div class="properties__card">
                <div class="properties__img overlay1">
                  <a href="#"><img src="/img/gallery/featured2.png" alt=""></a>
                </div>
                <div class="properties__caption">
                  <p>User Experience</p>
                  <h3><a href="#">Fundamental of UX for Application design</a></h3>
                  <p>
                    The automated process all your website tasks. Discover tools and techniques to engage effectively with vulnerable children and young people.
                  </p>
                  <div class="properties__footer d-flex justify-content-between align-items-center">
                    <div class="restaurant-name">
                      <div class="rating">
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star" />
                        <i class="fas fa-star-half" />
                      </div>
                      <p><span>(4.5)</span> based on 120</p>
                    </div>
                    <div class="price">
                      <span>$135</span>
                    </div>
                  </div>
                  <a href="#" class="border-btn border-btn2">Find out more</a>
                </div>
              </div>
            </div>
            <!-- Single -->
          </carousel>
        </no-ssr>
      </div>
    </div>
  </div>
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
