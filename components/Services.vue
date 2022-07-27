<template>
  <div class="service">
    <div class="title">
      <h2>Our Services</h2>
    </div>

    <div class="box">
      <div class="card">
        <i class="mdi mdi-auto-fix"></i>
        <h5>Creative Ideas</h5>
        <div class="pra">
          <p>
            We're creative, innovative and detail-oriented. We work hard to make
            your idea come to life with a unique identity that tells your story
            in a way that's never been done before.
          </p>
        </div>
      </div>

      <div class="card">
        <i class="mdi mdi-bullseye-arrow"></i>
        <h5>Flexible Concept</h5>
        <div class="pra">
          <p>
            We take our time to understand your design vision, always present it
            in a manner that is simple and effective, and are committed to
            producing a high-quality result that delivers on expectations
          </p>
        </div>
      </div>

      <div class="card">
        <i class="mdi mdi-flash"></i>
        <h5>Fast delivery</h5>
        <div class="pra">
          <p>
            We know that you have a goal - and we will work hard to meet it for
            you. Fast work means giving you the design after the schedule has
            been set
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Services',
}
</script>

<style scoped>
.service {
  background: var(--section);
  width: 100%;
  padding: 100px 0px;
}

.box {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 400px;
  flex-wrap: wrap;
}
.card {
  height: 365px;
  width: 335px;
  padding: 20px 35px;
  background: var(--background);
  border-radius: 20px;
  margin: 15px;
  position: relative;
  overflow: hidden;
  text-align: center;
}
.card i {
  font-size: 50px;
  display: block;
  text-align: center;
  margin: 25px 0px;
  color: var(--primary-color);
}
h5 {
  color: white;
  font-size: 23px;
  margin-bottom: 15px;
}
.pra p {
  color: #fcfc;
  font-size: 16px;
  line-height: 27px;
  margin-bottom: 25px;
}
.card .button {
  background-color: var(--primary-color);
  color: white;
  text-decoration: none;
  border: 2px solid transparent;
  font-weight: bold;
  padding: 9px 22px;
  border-radius: 30px;
  transition: 0.4s;
}
.card .button:hover {
  background-color: transparent;
  border: 2px solid var(--primary-color);
  cursor: pointer;
}
</style>
