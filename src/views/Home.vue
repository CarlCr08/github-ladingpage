<template>
  <div class="home">
    <Header/>
    <Hero/>
    <Enterprise/>
    <Companies/>
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Enterprise from '@/components/Enterprise.vue'
import Companies from '@/components/Companies.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Enterprise,
    Companies,
  }
}
</script>
