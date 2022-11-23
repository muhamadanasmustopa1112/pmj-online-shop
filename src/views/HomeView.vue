<template>
  <div class="home">
    <HeaderShayna />
    <HeroCarousel />
    <BannerCarousel />
    <InstaPmj />
    <PartnerPmj />
    <FooterPmj />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import BannerCarousel from '@/components/BannerCarousel.vue';
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroCarousel from '@/components/HeroCarousel.vue';
import InstaPmj from '@/components/InstaPmj.vue';
import PartnerPmj from '@/components/PartnerPmj.vue';
import FooterPmj from '@/components/FooterPmj.vue';


export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroCarousel,
    BannerCarousel,
    InstaPmj,
    PartnerPmj,
    FooterPmj
}
}
</script>
