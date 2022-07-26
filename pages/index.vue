<template>
  <div class="home">
    <Hero />
    <About />
    <Services />
  </div>
</template>

<script>
import Hero from '../components/Hero'
import About from '../components/About'
import Services from '../components/Services'
export default {
  name: 'IndexPage',
  components: { Hero, About, Services },
}
</script>
