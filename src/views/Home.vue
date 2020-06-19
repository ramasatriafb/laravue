<template>
  <div class="home">
    <HeaderShayna/>
    <Hero/>
    <WomanShayna/>
    <InstagramSection/>
    <PartnerSection/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import Hero from '@/components/Hero.vue'
import WomanShayna from '@/components/WomanShayna.vue'
import InstagramSection from '@/components/InstagramSection.vue'
import PartnerSection from '@/components/PartnerSection.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    Hero,
    WomanShayna,
    InstagramSection,
    PartnerSection,
    Footer
  }
}
</script>
