<template>
  <div class="home">
    <Header/>
    <Hero/>
    <Enterprise/>
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Enterprise from '@/components/Enterprise.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Enterprise,
  }
}
</script>
