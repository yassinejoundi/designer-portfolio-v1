<template>
  <div class="service">
    <div class="title">
      <h2>Our Services</h2>
    </div>

    <div class="box">
      <div class="card">
        <i class="fas fa-bars"></i>
        <h5>Web Development</h5>
        <div class="pra">
          <p>
            Every website should be built with two primary goals: Firstly, it
            needs to work across all devices. Secondly, it needs to be fast as
            possible.
          </p>

          <p style="text-align: center">
            <a class="button" href="#">Read More</a>
          </p>
        </div>
      </div>

      <div class="card">
        <i class="far fa-user"></i>
        <h5>Web Development</h5>
        <div class="pra">
          <p>
            Every website should be built with two primary goals: Firstly, it
            needs to work across all devices. Secondly, it needs to be fast as
            possible.
          </p>

          <p style="text-align: center">
            <a class="button" href="#">Read More</a>
          </p>
        </div>
      </div>

      <div class="card">
        <i class="far fa-bell"></i>
        <h5>Web Development</h5>
        <div class="pra">
          <p>
            Every website should be built with two primary goals: Firstly, it
            needs to work across all devices. Secondly, it needs to be fast as
            possible.
          </p>

          <p style="text-align: center">
            <a class="button" href="#">Read More</a>
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
  background: #101010;
  width: 100%;
  padding: 100px 0px;
}
.title h2 {
  color: white;
  font-size: 75px;
  width: 1130px;
  margin: 30px auto;
  text-align: center;
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
  background: #191919;
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
  color: #f9004d;
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
  background-color: #f9004d;
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
  border: 2px solid #f9004d;
  cursor: pointer;
}
</style>
