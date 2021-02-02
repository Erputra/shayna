<template>
  <div class="home">
    <Header />
    <Hero />
    <WomenBanner/>
    <Instagram/>
    <LogosPartner/>
    <RelatedProduct/>
    <Footer/>
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Hero from "../components/Hero";
import WomenBanner from "../components/WomenBanner"
import Instagram from "../components/Instagram"
import LogosPartner from "../components/Logos"
import Footer from "../components/Footer"

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    WomenBanner,
    Instagram,
    LogosPartner,
    Footer,
    },
};
</script>
