<template>
  <q-page class="blog-section ptb90">
    <div class="row flex-center container">
      <div class="container q-px-lg">
        <div class="col-lg-12">
          <div class="title-bl text-center wow fadeIn" data-wow-duration="2s">
            <div class="title color-white">Our latest Posts:</div>
            <div class="subtitle">Frash news</div>
          </div>
          <div class="title-description mt30 fweight-300 text-center">
            Pork chop pastrami meatball, picanha salami capicola drumstick tri-tip flank short loin
            <br />strip steak prosciutto leberkas jowl fatback.
          </div>
        </div>
      </div>
    </div>
    <div class="bg-wrapper each-element mt90 clearfix">
      <div class="row flex-center">
        <div class="container q-px-lg">
          <div class="row">
            <q-item class="item q-px-md col-lg-4 col-md-4 col-sm-12 col-sx-12">
              <q-btn to="/" class="item-wrap">
                <div class="image">
                  <img src="statics/images/blog-img-1.jpg" alt class="img-responsive" />
                </div>
                <div class="item-info equal-height">
                  <div class="item-header table fsize-14 fweight-700 uppercase width-100">
                    <div class="table-cell platform">xbox</div>
                    <div class="table-cell color-2 text-right">mar 14, 2018</div>
                  </div>
                  <div
                    class="item-title mt20"
                    data-trim="40"
                  >Cow biltong pork belly kielbasa shankle</div>
                  <div
                    class="item-text mt25 lheight-26"
                    data-trim="130"
                  >Turducken cupim hamburger beef ribs picanha, drumstick buffalo tri-tip cow. Turducken prosciutto shank pork chop.</div>
                </div>
                <div class="author-comment table width-100">
                  <div class="table-cell valign-middle">
                    <i class="fa fa-user color-1 fsize-14" aria-hidden="true"></i>
                    <span class="color-2 ml5">by Admin</span>
                  </div>
                  <div class="table-cell valign-middle text-right">
                    <i class="fa fa-comment color-1 fsize-14" aria-hidden="true"></i>
                    <span class="color-2 ml5">126</span>
                  </div>
                </div>
              </q-btn>
            </q-item>
            <q-item class="item q-px-md col-lg-4 col-md-4 col-sm-12 col-sx-12">
              <q-btn to="/" class="item-wrap">
                <div class="image">
                  <img src="statics/images/blog-img-2.jpg" alt class="img-responsive" />
                </div>
                <div class="item-info equal-height">
                  <div class="item-header table fsize-14 fweight-700 uppercase width-100">
                    <div class="table-cell platform">ps 3</div>
                    <div class="table-cell color-2 text-right">mar 18, 2018</div>
                  </div>
                  <div class="item-title mt20" data-trim="40">Cow short ribs beef strip steak jowl</div>
                  <div class="item-text mt25 lheight-26" data-trim="130">
                    Capicola beef ribs pastrami biltong pork chop corned beef alcatra tail landjaeger. Spare ribs t-bone buffalo capicola, pork
                    belly.
                  </div>
                </div>
                <div class="author-comment table width-100">
                  <div class="table-cell valign-middle">
                    <i class="fa fa-user color-1 fsize-14" aria-hidden="true"></i>
                    <span class="color-2 ml5">by Admin</span>
                  </div>
                  <div class="table-cell valign-middle text-right">
                    <i class="fa fa-comment color-1 fsize-14" aria-hidden="true"></i>
                    <span class="color-2 ml5">452</span>
                  </div>
                </div>
              </q-btn>
            </q-item>
            <q-item class="item q-px-md col-lg-4 col-md-4 col-sm-12 col-sx-12">
              <q-btn to="/" class="item-wrap">
                <div class="image">
                  <img src="statics/images/blog-img-3.jpg" alt class="img-responsive" />
                </div>
                <div class="item-info equal-height">
                  <div class="item-header table fsize-14 fweight-700 uppercase width-100">
                    <div class="table-cell platform">ps vita</div>
                    <div class="table-cell color-2 text-right">mar 23, 2018</div>
                  </div>
                  <div
                    class="item-title mt20"
                    data-trim="40"
                  >Boudin shankle pork belly turducken spare rib</div>
                  <div
                    class="item-text mt25 lheight-26"
                    data-trim="130"
                  >Capicola chicken rump biltong boudin corned beef prosciutto short loin pork chop fatback flank beef porchetta tenderloin.</div>
                </div>
                <div class="author-comment table width-100">
                  <div class="table-cell valign-middle">
                    <i class="fa fa-user color-1 fsize-14" aria-hidden="true"></i>
                    <span class="color-2 ml5">by Admin</span>
                  </div>
                  <div class="table-cell valign-middle text-right">
                    <i class="fa fa-comment color-1 fsize-14" aria-hidden="true"></i>
                    <span class="color-2 ml5">364</span>
                  </div>
                </div>
              </q-btn>
            </q-item>
          </div>
        </div>
      </div>
    </div>
  </q-page>
</template>


<script>
export default {
  name: "LatestPosts",
  data() {
    return {};
  }
};
</script>

<style scoped>
.item-wrap .q-btn__content {
  background: #292845 !important;
}
</style>