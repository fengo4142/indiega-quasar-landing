<template>
  <q-page class="ptb150">
    <div class="row flex-center">
      <div class="container q-px-lg">
        <div class="col-lg-12 st-tabs tabs mt70">
          <div class="tabs-nav">
            <q-tabs class="list-inline nav nav-tabs" v-model="stream">
              <q-tab name="stream-1" class="active col-lg-4 col-md-4 col-sm-12 col-xs-12">
                <div class="tab-title">Most popular streams</div>
              </q-tab>
              <q-tab name="stream-2" class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
                <div class="tab-title">Upcoming Competitions</div>
              </q-tab>
              <q-tab name="stream-3" class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
                <div class="tab-title">Prosciutto meatball flank</div>
              </q-tab>
            </q-tabs>
          </div>
          <q-tab-panels class="tab-content stream-bl relative" v-model="stream">
            <q-tab-panel
              name="stream-1"
              class="tab-pane row no-padding fade active in text-left clearfix"
              id="stream-1"
            >
              <div class="left-col col-lg-6 col-md-6 col-sm-12 col-xs-12">
                <div
                  class="video-bl equal-height"
                  data-vide-bg="mp4: http://denysthemes.com/html/riliant/assets/video/earth.mp4, webm: http://denysthemes.com/html/riliant/assets/video/earth.webm, ogv: http://denysthemes.com/html/riliant/assets/video/earth.ogv, poster: statics/images/585x550.jpg"
                  data-vide-options="className: 'video-main', posterType: jpg, loop: false, muted: false, position: center center, autoplay: false"
                >
                  <div class="buttonbar mt75">
                    <div id="play" class="play-show play relative fsize-24 inline-block">
                      <div class="pp-wrapper">
                        <i class="fa fa-play color-white" aria-hidden="true"></i>
                        <i class="fa fa-pause color-white" aria-hidden="true"></i>
                      </div>
                    </div>
                  </div>
                  <div class="video-bottom">
                    <div class="video-title">Tenderloin shoulder picanha rump</div>
                    <div class="mt15">
                      <div class="stream-img">
                        <img src="statics/images/stream-img-1.jpg" alt />
                      </div>
                      <div class="stream-img">
                        <img src="statics/images/stream-img-2.jpg" alt />
                      </div>
                      <div class="stream-img">
                        <img src="statics/images/stream-img-3.jpg" alt />
                      </div>
                      <div class="inline-block valign-middle color-white ml15">2569 watching now</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="right-col col-lg-6 col-md-6 col-sm-12 col-xs-12 equal-height">
                <div class="top-wrapp">
                  <div
                    class="fsize-24 fweight-700 font-agency color-white uppercase lheight-28"
                  >Create Your own channel and Start to Stream games now</div>
                  <div class="mt40 lheight-26">
                    Drumstick meatloaf capicola short ribs, pork chop cupim kielbasa jerky porchetta pancetta chicken pastrami turkey tenderloin
                    sausage. Pig buffalo alcatra meatball. T-bone hamburger bresaola kevin shank porchetta
                    ground. Round beef tail tri-tip. Short loin pork strip steak venison.
                  </div>
                  <q-btn class="btn gradient color-white plr40 ptb19 mt30">Get started now</q-btn>
                </div>
                <div class="bottom-wrapp mt40">
                  <div
                    class="fsize-24 fweight-700 font-agency uppercase color-white"
                  >9 136 streams from most recent games</div>
                  <div>267 347 watching now</div>
                </div>
              </div>
            </q-tab-panel>
            <q-tab-panel
              name="stream-2"
              class="tab-pane row no-padding fade in competition text-left clearfix"
              id="stream-2"
            >
              <div class="left-col col-lg-6 col-md-6 col-sm-12 col-xs-12">
                <div
                  class="image_bg equal-height"
                  style="background-image: url('statics/images/competition-full.jpg');"
                >
                  <div class="bottom-bar">
                    <q-btn href="#" class="btn gradient color-white plr50 ptb19">Contact us now</q-btn>
                  </div>
                </div>
              </div>
              <div class="right-col col-lg-6 col-md-6 col-sm-12 col-xs-12 equal-height">
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-1.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Shankle ribeye bacon</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-2.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Doner bresaola pork Kielbasa</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-3.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Kielbasa fatback alcatr</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-4.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Bacon tenderloin drumstick meatball</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
              </div>
            </q-tab-panel>
            <q-tab-panel
              name="stream-3"
              class="tab-pane row no-padding fade in competition text-left clearfix"
              id="stream-3"
            >
              <div class="left-col col-lg-6 col-md-6 col-sm-12 col-xs-12">
                <div
                  class="image_bg equal-height"
                  style="background-image: url('statics/images/competition-full.jpg');"
                >
                  <div class="bottom-bar">
                    <q-btn href="#" class="btn gradient color-white plr50 ptb19">Contact us now</q-btn>
                  </div>
                </div>
              </div>
              <div class="right-col col-lg-6 col-md-6 col-sm-12 col-xs-12 equal-height">
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-1.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Shankle ribeye bacon</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-2.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Doner bresaola pork Kielbasa</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-3.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Kielbasa fatback alcatr</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
                <div class="item-g">
                  <div class="img-com inline-block valign-middle">
                    <img src="statics/images/competition-4.jpg" alt />
                  </div>
                  <div class="info-bl inline-block valign-middle ml25">
                    <div
                      class="fsize-24 fweight-700 font-agency uppercase color-white"
                      data-trim="35"
                    >Bacon tenderloin drumstick meatball</div>
                    <div>267 347 participants</div>
                  </div>
                </div>
              </div>
            </q-tab-panel>
          </q-tab-panels>
        </div>
      </div>
    </div>
  </q-page>
</template>
<script>
export default {
  name: "StreamSection",
  data() {
    return {
      stream: "stream-1"
    };
  }
};
</script>

<style scoped>
.q-tab {
  border: 1px solid #292845;
}

.video-bl {
  position: relative;
}
.image_bg {
  height: 100% !important;
}
</style>