<template>
  <div class="hero">
    <div class="content">
      <h4>Hello, my name is</h4>
      <h1>Joundi <span>Yassine</span></h1>
      <h3>I'am a Web Developer.</h3>
      <div class="social">
        <a href="#"><i class="mdi mdi-facebook"></i></a>
        <a href="#"><i class="mdi mdi-instagram"></i></a>
        <a href="#"><i class="mdi mdi-linkedin"></i></a>
      </div>
    </div>
    <div class="profil"></div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<style scoped>
.hero {
  height: 100vh;
  width: 100%;
  background: #000;
  display: flex;
}

.hero div {
  width: 50%;
}

.profil {
  height: 100%;
  background-image: url(@/static/profil.jpg);
  background-size: cover;
  background-position: left;
}
</style>
