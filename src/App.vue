<script setup>
import HeroSection from './components/HeroSection.vue'
import NavbarMenu from './components/NavbarMenu.vue'
import TabbarMobile from './components/TabbarMobile.vue'
import ProductsSection from './components/ProductsSection.vue'
import FooterSection from './components/FooterSection.vue'
import CTASection from './components/CTASection.vue'
import VideosSection from './components/VideosSection.vue'
import SubscriptionSection from './components/SubscriptionSection.vue'
</script>

<template>
  <!-- Navbar -->

  <!-- Content -->
  <div class="w-full h-auto">
    <NavbarMenu />
    <HeroSection />
    <ProductsSection /> 
    <CTASection />  
    <VideosSection />
    <SubscriptionSection />

  </div>
  <!-- Footer -->
  <FooterSection/>
  <!-- Tabbar Mobile -->
  <TabbarMobile />
  
</template>


<style scoped>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
  }
</style>
