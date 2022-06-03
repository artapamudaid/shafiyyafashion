<template>
  <div class="home">

    <HeaderShafiyya/>
    <HeroShafiyya/>
    <WomenBanner/>
    <InstagramSection/>
    <PartnerLogo/>
    <FooterSection/>
   
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShafiyya from '@/components/HeaderShafiyya.vue'
import HeroShafiyya from '@/components/HeroShafiyya.vue'
import WomenBanner from '@/components/WomenBanner.vue'
import InstagramSection from '@/components/InstagramSection.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import FooterSection from '@/components/FooterSection.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderShafiyya,
    HeroShafiyya,
    WomenBanner,
    InstagramSection,
    PartnerLogo,
    FooterSection
}
}
</script>
