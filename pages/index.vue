<template>
  <div class="home">
    <Hero />
    <About />
    <Services />
    <Foot />
  </div>
</template>

<script>
import Hero from '~/components/Hero'
import About from '~/components/About'
import Services from '~/components/Services'
import Foot from '~/components/Foot'

export default {
  name: 'IndexPage',
  components: { Hero, About, Services, Foot },
}
</script>
