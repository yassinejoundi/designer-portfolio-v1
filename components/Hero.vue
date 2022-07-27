<template>
  <div class="hero">
    <div class="content">
      <h4>Hello, my name is</h4>
      <h1>Joundi <span>Yassine</span></h1>
      <h3>I'am a Graphic Designer.</h3>
      <div class="social">
        <a v-for="social in socials" :key="social.id" :href="social.link">
          <i :class="`mdi mdi-${social.icon}`"></i>
        </a>
      </div>
    </div>
    <div class="profil"></div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
  data() {
    return {
      socials: [
        {
          icon: 'facebook',
          link: 'https://www.facebook.com',
        },
        {
          icon: 'instagram',
          link: 'https://www.instagram.com',
        },
        {
          icon: 'linkedin',
          link: 'https://www.linkedin.com',
        },
      ],
    }
  },
}
</script>

<style scoped>
.hero {
  width: 100%;
  background: #000;
  display: flex;
  flex-wrap: wrap-reverse;
  align-items: center;
}

.hero > div {
  width: max(50%, 400px);
}

.content {
  padding: 20px;
}

.profil {
  height: 100vh;
  background-image: url(@/static/profil.jpg);
  background-size: cover;
  background-position: left;
}

@media only screen and (max-width: 600px) {
  .hero {
    position: relative;
  }

  .content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }

  .content:before {
    background-color: rgba(255, 255, 255, 0.01);
    backdrop-filter: blur(1px) saturate(100%) contrast(65%) brightness(130%);
    content: '';
    height: 100%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
    z-index: -1;
  }

  h4 {
    color: #fff !important;
  }
}
</style>
