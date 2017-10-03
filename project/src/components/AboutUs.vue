<template>
  <div class="about-page">
    <section class="hero is-small">
      <div class="hero-body">
        <div class="container">
          <h1>Our Mission</h1>
          <div>
            <br>
            <p class="ep-info">
              Exacta Plastics, Inc. serves their customers in USA and abroad with it's complete plastic injection molding and mold making capabilities in Southern California. To be competitive in mold making we also have our mold making facility offshore in India.
            </p>
            <br>
            <p class="ep-info">
              We also make challenging and nourishing environment for our employees and good return on investments to our stock holders.
            </p>
            <br>
          </div>
          <section class="container">
            <div class="columns">
              <div class="column is-half is-offset-one-quarter">
                <h1>Our Vision</h1>
              </div>
            </div>
            <br>
            <div class="columns">
              <div class="column ep-info">
                We want our customers old and new to call us everytime they have to troubleshoot or develop plastic related parts and/or assemblies.
              </div>
            </div>
            <img src="../assets/man-graph.jpg" alt="graph with metrics rising">
          </section>
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
  }
}
</script>

<style scoped>
h1 {
  font-size: 40px;
  text-align: center;
}
img {
  display: block;
  width: 60%;
  margin: auto;
  padding: 20px 0px;
}
.hero {
  background-color: #ECF0F1;
}
.ep-info {
  font-size: 20px;
  padding: 0 30px
}

</style>
