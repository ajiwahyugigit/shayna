<template>
  <div class="home">
    <HeaderShayna/>
    <HeroShayna/>
    <WomanShayna/>
    <InstaShayna/>
    <FartnerShayna/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomanShayna from '@/components/WomanShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import FartnerShayna from '@/components/FartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    FartnerShayna,
    FooterShayna
  }
}
</script>
