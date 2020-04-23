<template>
  <div class="home">
    <HeaderBakulPanen />
    <HeroBakulPanen />
    <WomanBakulPanen />
    <InstaBakulPanen />
    <PartnerBakulPanen />
    <FooterBakulPanen />
   
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderBakulPanen from '@/components/HeaderBakulPanen.vue'
import HeroBakulPanen from '@/components/HeroBakulPanen.vue'
import WomanBakulPanen from '@/components/WomanBakulPanen.vue'
import InstaBakulPanen from '@/components/InstaBakulPanen.vue'
import PartnerBakulPanen from '@/components/PartnerBakulPanen.vue'
import FooterBakulPanen from '@/components/FooterBakulPanen.vue'


export default {
  name: 'Home',
  components: {
    HeaderBakulPanen,
    HeroBakulPanen,
    WomanBakulPanen,
    InstaBakulPanen,
    PartnerBakulPanen,
    FooterBakulPanen
  }
}
</script>
