<template>
  <q-page class="price ptb150">
    <div class="row flex-center">
      <div class="container q-px-lg">
        <div class="title-bl text-center wow fadeIn" data-wow-duration="2s">
          <div class="title color-white">Our Pricing Plans</div>
          <div class="subtitle">Spesial Plans</div>
        </div>
        <div class="mt90 row">
          <div
            class="q-px-md col-lg-4 col-md-4 col-sm-12 col-xs-12 wow fadeInLeft"
            data-wow-duration="2s"
          >
            <div class="item standart text-center">
              <div
                class="ptb30 fsize-24 fweight-700 font-agency uppercase color-white"
              >Standard Plan</div>
              <div class="current-bl color-white pt25 pb20">
                <div class="font-agency fweight-700 lheight-30">
                  <span class="fsize-24">$</span>
                  <span class="fsize-48">39</span>
                  <span class="fsize-24">99</span>
                </div>
                <div class="fsize-14 uppercase fweight-700">Per mouth</div>
              </div>
              <div class="price-content equal-height">
                <div class="item-list">Pork Ground Found Biltong</div>
                <div class="item-list">Capicola Sausage Beef Ribs</div>
                <div class="item-list">Pork Doner Frankfurter</div>
              </div>
              <div class="text-center pb60">
                <q-btn to="/" class="btn border-btn color-white plr50 ptb19">Buy Plan Now</q-btn>
              </div>
            </div>
          </div>
          <div
            class="q-px-md col-lg-4 col-md-4 col-sm-12 col-xs-12 wow fadeInDown"
            data-wow-duration="1s"
          >
            <div class="item gold text-center">
              <div class="ptb30 fsize-24 fweight-700 font-agency uppercase color-white">Golden Plan</div>
              <div class="current-bl color-white pt25 pb20">
                <div class="font-agency fweight-700 lheight-30">
                  <span class="fsize-24">$</span>
                  <span class="fsize-48">59</span>
                  <span class="fsize-24">59</span>
                </div>
                <div class="fsize-14 uppercase fweight-700">Per mouth</div>
              </div>
              <div class="price-content equal-height">
                <div class="item-list">Doner Boudin Rump Picanha</div>
                <div class="item-list">Leberkas Kevin Drumstick</div>
                <div class="item-list">Beef Mignon Bresaola</div>
              </div>
              <div class="text-center pb60">
                <q-btn to="/" class="btn border-btn color-white plr50 ptb19">Buy Plan Now</q-btn>
              </div>
            </div>
          </div>
          <div
            class="q-px-md col-lg-4 col-md-4 col-sm-12 col-xs-12 wow fadeInRight"
            data-wow-duration="2s"
          >
            <div class="item platinum text-center">
              <div
                class="ptb30 fsize-24 fweight-700 font-agency uppercase color-white"
              >Platinum Plan</div>
              <div class="current-bl color-white pt25 pb20">
                <div class="font-agency fweight-700 lheight-30">
                  <span class="fsize-24">$</span>
                  <span class="fsize-48">89</span>
                  <span class="fsize-24">39</span>
                </div>
                <div class="fsize-14 uppercase fweight-700">Per mouth</div>
              </div>
              <div class="price-content equal-height">
                <div class="item-list">Bresaola Shoulder Venison</div>
                <div class="item-list">Frankfurter Cow Ribeye Kielbasa</div>
                <div class="item-list">Cupim Drumstick Tail Pancetta</div>
              </div>
              <div class="text-center pb60">
                <q-btn to="/" class="btn border-btn color-white plr50 ptb19">Buy Plan Now</q-btn>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  name: "PricingTable"
};
</script>