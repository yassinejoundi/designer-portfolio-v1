<template>
  <div class="about">
    <div class="main">
      <img :src="require('@/static/about.png')" />
      <div class="about-text">
        <h2>About Me</h2>
        <h5>Developer <span>& Designer</span></h5>
        <p>
          I am a front-end web developer. I can provide clean code and pixel
          perfect design. I also make the website more & more interactive with
          web animations.I can provide clean code and pixel perfect design. I
          also make the website more & more interactive with web animations.A
          responsive design makes your website accessible to all users,
          regardless of their device.
        </p>
        <button type="button">Let's Talk</button>
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
  width: 100%;
  padding: 100px 0px;
  background-color: #191919;
}
.about img {
  height: auto;
  width: 430px;
}
.about-text {
  width: 550px;
}
.main {
  width: 1130px;
  max-width: 95%;
  margin: 0 auto;
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
