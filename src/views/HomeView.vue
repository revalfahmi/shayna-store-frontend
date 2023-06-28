<template>
  <div class="home">
    <header-shayna />
    <hero-shayna />
    <woman-shayna />
    <instagram-shayna />
    <partner-shayna />
    <footer-shayna />
  </div>
</template>

<script>
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue';
import WomanShayna from '@/components/WomanShayna.vue';
import InstagramShayna from '@/components/InstagramShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstagramShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
