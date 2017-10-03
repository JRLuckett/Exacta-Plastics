<template>
  <div class="services-page">
    <section class="hero is-small">
      <div class="hero-body">
        <div class="container">
          <h1>Contact Us</h1>
          <img src="../assets/group.jpg" alt="group of engineers">
          <br>
          <a class="button is-large" href="mailto:jluckettt@gmail.com">Email</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
}
</script>

<style scoped>
h1 {
  font-size: 40px;
  text-align: center;
}
.hero {
  background-color: #ECF0F1;
}
.container {
  text-align: center;
}
a {
  margin-top: 20px;
  color: #ECF0F1;
  background-color: #09014C;
}
a:hover {
  color: #4FF3FC;
}
.ep-info {
  font-size: 20px;
  padding: 0 30px
}
</style>
