<template>
  <div class="home">
    <HeaderSutiono />
    <HeroSutiono />
    <BannerSutiono />
    <InstaSutiono />
    <LogoPartnerSutiono />
    <FooterSutiono />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSutiono from "@/components/HeaderSutiono.vue";
import HeroSutiono from "@/components/HeroSutiono.vue";
import BannerSutiono from "@/components/BannerSutiono.vue";
import InstaSutiono from "@/components/InstaSutiono.vue";
import LogoPartnerSutiono from "@/components/LogoPartnerSutiono.vue";
import FooterSutiono from "@/components/FooterSutiono.vue";

export default {
  name: "Home",
  components: {
    HeaderSutiono,
    HeroSutiono,
    BannerSutiono,
    InstaSutiono,
    LogoPartnerSutiono,
    FooterSutiono,
  },
};
</script>
