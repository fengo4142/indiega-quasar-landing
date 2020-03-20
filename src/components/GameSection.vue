<template>
  <q-page class="game-section row pt150 pb85">
    <div class="row flex-center">
      <div class="container q-px-lg">
        <div class="title-bl text-center wow fadeIn" data-wow-duration="2s">
          <div class="title color-white">UpComing Games:</div>
          <div class="subtitle">Coming soon</div>
        </div>
        <div class="tm-tabs tabs mt70">
          <div class="tabs-nav">
            <q-tabs class="flex wrap list-inline nav nav-tabs tabs-slider" v-model="tab">
              <q-tab name="tab1" class="col text-center">
                <div class="img-wrap">
                  <img src="statics/images/game-img-1.jpg" alt />
                </div>
                <div class="nav-header-bl mt25">
                  <div class="nav-title color-white">Fifal 2018</div>
                  <div class="date">Mar 18-20, 2018</div>
                </div>
              </q-tab>
              <q-tab name="tab2" class="gt-xs col text-center">
                <div class="img-wrap">
                  <img src="statics/images/game-img-2.jpg" alt />
                </div>
                <div class="nav-header-bl mt25">
                  <div class="nav-title color-white">Mix Combination</div>
                  <div class="date">Apr 25-27, 2018</div>
                </div>
              </q-tab>
              <q-tab name="tab3" class="gt-sm col text-center">
                <div class="img-wrap">
                  <img src="statics/images/game-img-3.jpg" alt />
                </div>
                <div class="nav-header-bl mt25">
                  <div class="nav-title color-white">Forza Jacson</div>
                  <div class="date">Mar 11, 2019</div>
                </div>
              </q-tab>
              <q-tab name="tab4" class="gt-md col text-center">
                <div class="img-wrap">
                  <img src="statics/images/game-img-4.jpg" alt />
                </div>
                <div class="nav-header-bl mt25">
                  <div class="nav-title color-white">NO MAN’S SKY</div>
                  <div class="date">Sept 15, 2019</div>
                </div>
              </q-tab>
            </q-tabs>
          </div>
          <q-tab-panels class="tab-content relative mt90" v-model="tab">
            <q-tab-panel
              name="tab1"
              class="tab-pane row fade active in text-left clearfix"
              id="tab-item-1"
            >
              <div
                class="tab-info col col-lg-6 col-md-12 col-sm-12 col-xs-12 ptb90 pl100 equal-height"
              >
                <div class="tab-head table uppercase fsize-14 fweight-700 width-100">
                  <div class="table-cell valign-middle ws-20 color-1">New games action</div>
                  <div class="table-cell valign-middle text-right">Apr 25-27, 2018</div>
                </div>
                <div
                  class="uppercase fsize-32 fweight-700 font-agency color-white lheight-normal"
                >Fifal 2018</div>
                <div class="mt50 lheight-26 fweight-300">
                  <p>
                    Andouille frankfurter hamburger, swine leberkas tenderloin cupim. Ground round ball tip
                    pastrami, turducken chicken porchetta fatback frankfurter. Pig kielbasa jowl strip.
                  </p>
                  <p>
                    Steak sausage pork loin bacon tri-tip meatball shoulder cupim beef pork chop kevin boudin.
                    Short loin pig meatball ham landjaeger pastrami. Drumstick ham hock chuck pork belly
                    chicken prosciutto biltong salami ham pancetta.
                  </p>
                </div>
                <div class="mt60 table g-bottom">
                  <div class="table-cell valign-middle q-mr-md">
                    <q-btn to="single-game.html" class="btn gradient color-white">Read more</q-btn>
                  </div>
                  <div class="q-pl-lg rating table-cell valign-middle text-right">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                  </div>
                </div>
              </div>
              <div class="tab-img col col-lg-6 col-md-12 col-sm-12 col-xs-12 pr0 equal-height">
                <div class="image-bl">
                  <q-img class="game-full-img" src="statics/images/game-slide-img-1.jpg" alt />
                </div>
              </div>
            </q-tab-panel>

            <q-tab-panel
              name="tab2"
              class="tab-pane row fade in text-left clearfix"
              id="tab-item-2"
            >
              <div
                class="tab-info col col-lg-6 col-md-12 col-sm-12 col-xs-12 ptb90 pl100 equal-height"
              >
                <div class="tab-head table uppercase fsize-14 fweight-700 w-100">
                  <div class="table-cell valign-middle ws-20 color-1">New games action</div>
                  <div class="table-cell valign-middle text-right">Apr 25-27, 2018</div>
                </div>
                <div
                  class="uppercase fsize-32 fweight-700 font-agency color-white lheight-normal"
                >Mix Combination</div>
                <div class="mt50 lheight-26 fweight-300">
                  <p>
                    Andouille frankfurter hamburger, swine leberkas tenderloin cupim. Ground round ball tip
                    pastrami, turducken chicken porchetta fatback frankfurter. Pig kielbasa jowl strip.
                  </p>
                  <p>
                    Steak sausage pork loin bacon tri-tip meatball shoulder cupim beef pork chop kevin boudin.
                    Short loin pig meatball ham landjaeger pastrami. Drumstick ham hock chuck pork belly
                    chicken prosciutto biltong salami ham pancetta.
                  </p>
                </div>
                <div class="mt60 table g-bottom">
                  <div class="table-cell valign-middle q-mr-md">
                    <q-btn to="single-game.html" class="btn gradient color-white">Read more</q-btn>
                  </div>
                  <div class="q-pl-lg rating table-cell valign-middle text-right">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                  </div>
                </div>
              </div>
              <div class="tab-img col col-lg-6 col-md-12 col-sm-12 col-xs-12 pr0 equal-height">
                <div class="image-bl">
                  <q-img class="game-full-img" src="statics/images/game-slide-img-1.jpg" alt />
                </div>
              </div>
            </q-tab-panel>
            <q-tab-panel
              name="tab3"
              class="tab-pane row fade in text-left clearfix"
              id="tab-item-3"
            >
              <div
                class="tab-info col col-lg-6 col-md-12 col-sm-12 col-xs-12 ptb90 pl100 equal-height"
              >
                <div class="tab-head table uppercase fsize-14 fweight-700 w-100">
                  <div class="table-cell valign-middle ws-20 color-1">New games action</div>
                  <div class="table-cell valign-middle text-right">Apr 25-27, 2018</div>
                </div>
                <div
                  class="uppercase fsize-32 fweight-700 font-agency color-white lheight-normal"
                >Forza Jacson</div>
                <div class="mt50 lheight-26 fweight-300">
                  <p>
                    Andouille frankfurter hamburger, swine leberkas tenderloin cupim. Ground round ball tip
                    pastrami, turducken chicken porchetta fatback frankfurter. Pig kielbasa jowl strip.
                  </p>
                  <p>
                    Steak sausage pork loin bacon tri-tip meatball shoulder cupim beef pork chop kevin boudin.
                    Short loin pig meatball ham landjaeger pastrami. Drumstick ham hock chuck pork belly
                    chicken prosciutto biltong salami ham pancetta.
                  </p>
                </div>
                <div class="mt60 table g-bottom">
                  <div class="table-cell valign-middle">
                    <q-btn to="single-game.html" class="btn gradient color-white">Read more</q-btn>
                  </div>
                  <div class="q-pl-lg rating table-cell valign-middle text-right width-100">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                  </div>
                </div>
              </div>
              <div class="tab-img col col-lg-6 col-md-12 col-sm-12 col-xs-12 pr0 equal-height">
                <div class="image-bl">
                  <q-img class="game-full-img" src="statics/images/game-slide-img-1.jpg" alt />
                </div>
              </div>
            </q-tab-panel>
            <q-tab-panel
              name="tab4"
              class="tab-pane row fade in text-left clearfix"
              id="tab-item-4"
            >
              <div
                class="tab-info col col-lg-6 col-md-12 col-sm-12 col-xs-12 ptb90 pl100 equal-height"
              >
                <div class="tab-head table uppercase fsize-14 fweight-700 w-100">
                  <div class="table-cell valign-middle ws-20 color-1">New games action</div>
                  <div class="table-cell valign-middle text-right">Apr 25-27, 2018</div>
                </div>
                <div
                  class="uppercase fsize-32 fweight-700 font-agency color-white lheight-normal"
                >NO MAN’S SKY</div>
                <div class="mt50 lheight-26 fweight-300">
                  <p>
                    Andouille frankfurter hamburger, swine leberkas tenderloin cupim. Ground round ball tip
                    pastrami, turducken chicken porchetta fatback frankfurter. Pig kielbasa jowl strip.
                  </p>
                  <p>
                    Steak sausage pork loin bacon tri-tip meatball shoulder cupim beef pork chop kevin boudin.
                    Short loin pig meatball ham landjaeger pastrami. Drumstick ham hock chuck pork belly
                    chicken prosciutto biltong salami ham pancetta.
                  </p>
                </div>
                <div class="mt60 table g-bottom">
                  <div class="table-cell valign-middle">
                    <q-btn to="single-game.html" class="btn gradient color-white">Read more</q-btn>
                  </div>
                  <div class="q-pl-lg rating table-cell valign-middle text-right">
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                    <i class="fa fa-star" aria-hidden="true"></i>
                  </div>
                </div>
              </div>
              <div class="tab-img col col-lg-6 col-md-12 col-sm-12 col-xs-12 pr0 equal-height">
                <div class="image-bl">
                  <q-img class="game-full-img" src="statics/images/game-slide-img-1.jpg" alt />
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
  name: "GameSection",
  data() {
    return {
      tab: "tab1"
    };
  }
};
</script>

<style scoped>
.btn {
  min-width: 150px;
  padding: 10px 20px;
}
.q-panel-parent {
  overflow: initial;
}
.nav-tabs .q-tab {
  min-width: 220px;
}
</style>