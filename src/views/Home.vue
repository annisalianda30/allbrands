<template>
  <div class="home">
   <HeaderAllbrands/>
   <HeroAllbrands/>
   <WomanAllbrands/>
   <InstaAllbrands/>
   <Partner/>
   <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderAllbrands from '@/components/HeaderAllbrands.vue'
import HeroAllbrands from '@/components/HeroAllbrands.vue'
import WomanAllbrands from '@/components/WomanAllbrands.vue'
import InstaAllbrands from '@/components/InstaAllbrands.vue'
import Partner from '@/components/Partner.vue'
import Footer from '@/components/Footer.vue'



export default {
  name: 'Home',
  components: {
    HeaderAllbrands,
    HeroAllbrands,
    WomanAllbrands,
    InstaAllbrands,
    Partner,
    Footer
  }
};
</script>
