<template>
  <footer>
    <p>Joundi Yassine</p>
    <p>Let Me Get You A Beautiful Designs</p>
    <div class="social">
      <a v-for="social in socials" :key="social.id" :href="social.link">
        <i :class="`mdi mdi-${social.icon}`"></i>
      </a>
    </div>
    <p class="end">
      CopyRight By
      <a href="https://www.linkedin.com/in/yassinejoundi">Joundi Yassine</a>
    </p>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
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
footer {
  position: relative;
  width: 100%;
  height: 400px;
  background: var(--section);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
footer p:nth-child(1) {
  font-size: 30px;
  color: white;
  margin-bottom: 20px;
  font-weight: bold;
}
footer p:nth-child(2) {
  color: white;
  font-size: 17px;
  text-align: center;
  line-height: 26px;
}
.end {
  position: absolute;
  color: var(--primary-color);
  bottom: 35px;
  font-size: 14px;
}

.end a {
  color: var(--primary-color);
}
</style>
