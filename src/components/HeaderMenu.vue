<template>
  <q-page class="header-line-wrapper">
    <header class="header-wrapper fixed-top plr100">
      <q-item class="row height-100p width-100">
        <q-item-section class="logo row valign-middle text-left">
          <q-btn unelevated to="index.html" class="no-shadow no-ripple">
            <img src="statics/images/logo.png" alt class="img-responsive inline-block" />
          </q-btn>
        </q-item-section>
        <q-item-section
          class="row menu-list valign-top text-center vm-sm gt-sm"
          :class="mobileMenu"
        >
          <q-btn label="Home">
            <q-menu
              :offset="[60, 15]"
              :content-style="{ backgroundColor: '#1e1d32', color: '#fff', fontWeight: '500'}"
            >
              <q-list style="min-width: 200px">
                <q-item to="/" class="q-py-lg text-white text-center" clickable>
                  <q-item-section>About</q-item-section>
                </q-item>
                <q-separator class="seperator" dark />
                <q-item to="/" class="q-py-lg text-white text-center" clickable>
                  <q-item-section>404</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
          <q-btn label="Gallery">
            <q-menu
              :offset="[60, 15]"
              :content-style="{ backgroundColor: '#1e1d32', color: '#fff', fontWeight: '500'}"
            >
              <q-list style="min-width: 200px">
                <q-item class="q-py-lg text-white text-center" clickable>
                  <q-item-section>Gallery Regular</q-item-section>
                </q-item>
                <q-separator class="seperator" dark />
                <q-item class="q-py-lg text-white text-center" clickable>
                  <q-item-section>Single image</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
        </q-item-section>
        <q-item-section class="row valign-top text-right">
          <div class="main-menu">
            <span class="toggle_menu" :class="toggleMenu" clickable @click="onExpandMenu">
              <span></span>
            </span>
          </div>
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
      </q-item>
    </header>
  </q-page>
</template>


<script>
export default {
  name: "DefaultHeader",
  data() {
    return {
      mobileMenu: "",
      toggleMenu: ""
    };
  },
  methods: {
    onExpandMenu() {
      this.mobileMenu = this.mobileMenu === "" ? "mobile-menu" : "";
      this.toggleMenu = this.toggleMenu === "" ? "open" : "";
    }
  }
};
</script>

<style>
.logo {
  min-width: 200px;
}
.mobile-menu {
  position: absolute;
  height: 1000px;
  top: 0;
  left: 0;
  right: 0;
  background: #1e1d32;
  padding: 0 30px;
  overflow-y: auto;
  opacity: 1;
  visibility: visible;
  transition: all 0.3s ease-out;
  padding-top: 100px !important;
  display: flex !important;
  flex-direction: column !important;
  align-items: flex-start;
  justify-content: stretch;
}
.menu-list {
  flex-direction: row;
}
.q-focus-helper {
  display: none;
}
.q-btn__wrapper:before {
  display: none;
}
.seperator {
  width: 80%;
  margin: auto;
}
</style>