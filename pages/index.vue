<template>
  <div class="home">
    <Hero />
    <About />
    <Services />
    <Gallery />
    <Foot />
  </div>
</template>

<script>
import Hero from '~/components/Hero'
import About from '~/components/About'
import Services from '~/components/Services'
import Foot from '~/components/Foot'
import Gallery from '~/components/Gallery'

export default {
  name: 'IndexPage',
  components: { Hero, About, Services, Foot, Gallery },
}
</script>
