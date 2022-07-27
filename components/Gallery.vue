<template>
  <div class="gallery">
    <div class="title">
      <h2>Our Gallery</h2>
    </div>

    <div class="photos">
      <img
        v-for="i in 9"
        :key="i"
        :src="require(`@/static/gallery/gallery-${i}.jpg`)"
      />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.gallery {
  padding: 100px 0px;
  background-color: var(--background);
}

.photos {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.photos img {
  width: 335px;
  height: 450px;
  border-radius: 20px;
  margin: 15px;
}
</style>
