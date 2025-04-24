<script setup>
import BenefitsSection from './components/BenefitsSection.vue';
import FAQSection from './components/FAQSection.vue';
import FooterSection from './components/FooterSection.vue';
import HeaderSection from './components/HeaderSection.vue'
import HeroSection from './components/HeroSection.vue';
import PricingPlansSection from './components/PricingPlansSection.vue';
</script>

<template>
  <HeaderSection />
  <HeroSection />
  <BenefitsSection />
  <PricingPlansSection />
  <FAQSection />
  <FooterSection />
  <!-- <div>
    <a href="https://vite.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <router-view /> -->
</template>
