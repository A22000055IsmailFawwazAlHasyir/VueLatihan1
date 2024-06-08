<script setup lang="js">
import { Footer, Header } from '@/components'
import { CompanySection, FeaturesSection, PricingSection, ProductSection } from '@/views/home'
</script>

<template>
  <Header/>
  <main>
    <ProductSection />
    <FeaturesSection />
    <PricingSection />
    <CompanySection />
  </main>
  <Footer />
</template>
