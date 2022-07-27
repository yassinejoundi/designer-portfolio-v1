<template>
  <div class="about">
    <div class="main">
      <img :src="require('@/static/about.png')" />
      <div class="about-text">
        <h2>About Me</h2>
        <h5>Graphic <span>Designer</span></h5>
        <p>
          I'm a full-time graphic designer and photographer with over 10 years
          of experience. I specialize in logo design and branding, along with
          custom logos, social media graphics and print collateral such as
          business cards, flyers and brochures. I have more than 4k followers on
          Instagram and am able to grow your brand through social media
          marketing.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About',
}
</script>

<style scoped>
.about {
  padding: 100px 0px;
  background-color: var(--background);
}
.about img {
  height: auto;
  width: 400px;
}
.about-text {
  width: 450px;
  padding: 0 5px 0 20px;
}
.main {
  width: 90%;
  /*margin: 0 auto;*/
  display: flex;
  align-items: center;
  justify-content: space-around;
  flex-wrap: wrap-reverse;
}
.about-text h2 {
  color: white;
  font-size: 75px;
  text-transform: capitalize;
  margin-bottom: 20px;
}
.about-text h5 {
  color: white;
  letter-spacing: 2px;
  font-size: 22px;
  margin-bottom: 25px;
  text-transform: capitalize;
}
.about-text p {
  color: #fcfc;
  letter-spacing: 1px;
  line-height: 28px;
  font-size: 18px;
  margin-bottom: 45px;
}
</style>
