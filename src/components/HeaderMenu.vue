<template>
  <q-page class="header-line-wrapper">
    <header class="header-wrapper fixed-top plr100">
      <div class="table height-100p width-100">
        <q-item-section class="table-cell valign-middle text-left">
          <a href="index.html" class="logo">
            <img src="statics/images/logo.png" alt class="img-responsive inline-block" />
          </a>
        </q-item-section>
        <q-item-section class="table-cell valign-top text-center vm-sm">
          <div class="main-menu">
            <span class="toggle_menu">
              <span></span>
            </span>
            <ul class="menu clearfix">
              <li class="inline-block active">
                <a href="index.html">Homepage</a>
              </li>
              <li class="inline-block menu-item-has-children">
                <a href="#">Pages</a>
                <ul class="sub-menu">
                  <li>
                    <a href="about.html">About</a>
                  </li>
                  <li>
                    <a href="404.html">404</a>
                  </li>
                  <li>
                    <a href="faq.html">FAQ</a>
                  </li>
                  <li class="menu-item-has-children">
                    <a href="team.html">Team</a>
                    <ul class="sub-menu">
                      <li>
                        <a href="single-team.html">Member profile</a>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <a href="typography.html">Typography</a>
                  </li>
                  <li>
                    <a href="price.html">Pricing plans</a>
                  </li>
                  <li>
                    <a href="testimonials.html">Testimonials</a>
                  </li>
                  <li>
                    <a href="statistic.html">Statistic</a>
                  </li>
                </ul>
              </li>
              <li class="inline-block menu-item-has-children">
                <a href="#">Gallery</a>
                <ul class="sub-menu">
                  <li>
                    <a href="gallery-regular.html">Gallery Regular</a>
                  </li>
                  <li>
                    <a href="gallery-masonry.html">Gallery Masonry</a>
                  </li>
                  <li>
                    <a href="gallery-full.html">Gallery Fullwidth</a>
                  </li>
                  <li>
                    <a href="gallery-extended.html">Gallery Extended</a>
                  </li>
                  <li>
                    <a href="single-image.html">Single image</a>
                  </li>
                </ul>
              </li>
            </ul>
          </div>
        </q-item-section>
        <q-item-section class="table-cell valign-top text-right">
          <div class="right-bl">
            <div class="search-wrapper inline-block valign-middle">
              <i class="fa fa-search color-white fsize-28" aria-hidden="true"></i>
              <form class="search-content" action="#">
                <q-input type="text" placeholder="Search Keyword..." />
                <q-btn class="color-white">
                  <i class="fa fa-search" aria-hidden="true"></i>
                </q-btn>
              </form>
            </div>
            <q-btn class="header-btn btn ml25 color-white gt-sm xl-hidden">Join us Now</q-btn>
          </div>
        </q-item-section>
      </div>
    </header>
  </q-page>
</template>


<script>
export default {
  name: "DefaultHeader",
  data() {
    return {};
  }
};
</script>