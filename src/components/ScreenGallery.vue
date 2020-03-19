<template>
  <section class="gallery main-gallery ptb150">
    <div class="row flex-center container">
      <div class="col-12 q-px-md">
        <div class="title-bl text-center wow fadeIn" data-wow-duration="2s">
          <div class="title color-white">Screenshots gallery</div>
          <div class="subtitle">All New Images</div>
        </div>
      </div>
      <div class="container q-px-lg">
        <div class="grid-wrapper mt70">
          <div class="filter_container text-center">
            <div class="filter-item active" data-filter="all">All</div>
            <div class="filter-item" data-filter="origin">Origin</div>
            <div class="filter-item" data-filter="playstation-4">Playstation 4</div>
            <div class="filter-item" data-filter="steam">Steam</div>
            <div class="filter-item" data-filter="uplay">Uplay</div>
            <div class="filter-item" data-filter="xbox-one">Xbox one</div>
          </div>
          <div class="item_container relative mt40">
            <div class="item origin col-lg-4 col-md-4 col-sm-4 col-xs-12">
              <div class="item-content">
                <div class="image-bl">
                  <img src="statics/images/gallery/gallery-1.jpg" alt />
                </div>
                <div class="item-info">
                  <div class="info-bl text-center">
                    <a
                      href="#"
                      data-trim="40"
                      class="item-title color-white fsize-24 fweight-700 font-agency uppercase"
                    >Using Banner Stands To Increase Trade</a>
                    <div class="text-center mt30">
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-search" aria-hidden="true"></i>
                      </a>
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-thumb-tack" aria-hidden="true"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item playstation-4 col-lg-4 col-md-4 col-sm-4 col-xs-12">
              <div class="item-content">
                <div class="image-bl">
                  <img src="statics/images/gallery/gallery-2.jpg" alt />
                </div>
                <div class="item-info">
                  <div class="info-bl text-center">
                    <a
                      href="#"
                      data-trim="40"
                      class="item-title color-white fsize-24 fweight-700 font-agency uppercase"
                    >Using Banner Stands To Increase Trade</a>
                    <div class="text-center mt30">
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-search" aria-hidden="true"></i>
                      </a>
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-thumb-tack" aria-hidden="true"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item uplay col-lg-4 col-md-4 col-sm-4 col-xs-12">
              <div class="item-content">
                <div class="image-bl">
                  <img src="statics/images/gallery/gallery-4.jpg" alt />
                </div>
                <div class="item-info">
                  <div class="info-bl text-center">
                    <a
                      href="#"
                      data-trim="40"
                      class="item-title color-white fsize-24 fweight-700 font-agency uppercase"
                    >Using Banner Stands To Increase Trade</a>
                    <div class="text-center mt30">
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-search" aria-hidden="true"></i>
                      </a>
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-thumb-tack" aria-hidden="true"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item steam xbox-one col-lg-8 col-md-8 col-sm-8 col-xs-12">
              <div class="item-content">
                <div class="image-bl">
                  <img src="statics/images/gallery/gallery-3.jpg" alt />
                </div>
                <div class="item-info">
                  <div class="info-bl text-center">
                    <a
                      href="#"
                      data-trim="40"
                      class="item-title color-white fsize-24 fweight-700 font-agency uppercase"
                    >Using Banner Stands To Increase Trade</a>
                    <div class="text-center mt30">
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-search" aria-hidden="true"></i>
                      </a>
                      <a href="#" class="item-btn inline-block valign-middle">
                        <i class="fa fa-thumb-tack" aria-hidden="true"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-12 text-center mt50">
            <a href="#" class="btn border-btn plr50 ptb19 color-white">Discover more</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ScreenGallery",
  data() {
    return {};
  }
};
</script>

<style scoped>
.grid-wrapper {
  max-width: 1120px;
  margin: auto;
}
.item_container {
  min-height: 626px;
}
.origin {
  left: 0px;
  top: 0px;
  transform: translateX(0px) translateY(0px);
  display: block;
}
.playstation-4 {
  left: 0px;
  top: 0px;
  transform: translateX(390px) translateY(0px);
  display: block;
}

.uplay {
  left: 0px;
  top: 0px;
  transform: translateX(780px) translateY(0px);
  display: block;
}

.steam {
  left: 0px;
  top: 0px;
  transform: translateX(0px) translateY(314px);
  display: block;
}
</style>