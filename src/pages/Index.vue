<template>
  <q-page>
    <!-- HEADER START -->
    <HeaderMenu></HeaderMenu>
    <!-- HEADER END -->

    <!-- SLIDER START -->
    <HeroSlider></HeroSlider>
    <!-- SLIDER END -->

    <!-- GAME SECTION START -->
    <GameSection></GameSection>
    <!-- GAME SECTION END -->

    <!-- BLOG SECTION START -->
    <LatestPosts></LatestPosts>
    <!-- BLOG SECTION END -->

    <!-- GALLERY SECTION START -->
    <StreamSection></StreamSection>
    <!-- GALLERY SECTION END -->

    <!-- PRICE SECTION START -->
    <PricingTable></PricingTable>
    <!-- PRICE SECTION END -->

    <!-- FAQ SECTION START -->
    <Faq></Faq>
    <!-- FAQ SECTION END -->

    <!-- REGISTER SECTION START -->
    <RegisterForm></RegisterForm>
    <!-- REGISTER SECTION END -->

    <!-- FOOTER START -->
    <FooterSection></FooterSection>
    <!-- FOOTER END -->
    <a href="#" id="toTop" class="color-white">
      <i class="fa fa-angle-up fsize-14" aria-hidden="true"></i>
    </a>
  </q-page>
</template>

<script>
import HeaderMenu from "../components/HeaderMenu";
import HeroSlider from "../components/HeroSlider";
import GameSection from "../components/GameSection";
import LatestPosts from "../components/LatestPosts";
import StreamSection from "../components/StreamSection";
import PricingTable from "../components/PricingTable";
import Faq from "../components/Faq";
import RegisterForm from "../components/RegisterForm";
import FooterSection from "../components/FooterSection";

export default {
  name: "PageIndex",
  components: {
    HeaderMenu,
    HeroSlider,
    GameSection,
    LatestPosts,
    StreamSection,
    PricingTable,
    Faq,
    RegisterForm,
    FooterSection
  }
};
</script>

<style scoped>
.row {
  display: block;
}
.main-slider {
  position: relative;
}
.bg-white {
  background: transparent !important;
}
.tab-img {
  height: 612px;
}
</style>
