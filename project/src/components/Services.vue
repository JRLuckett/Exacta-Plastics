<template>
  <div class="services-page">
    <section class="hero is-small">
      <div class="hero-body">
        <div class="container">
          <h1>What We Do</h1>
          <div class="columns is-mobile">
            <div class="column is-half left">
              <div class="box">
                <p class="title">Services</p>
                <div class="content">
                  <i class="fa fa-cogs" aria-hidden="true"> Tooling</i>
                  <br>
                  <i class="fa fa-cogs" aria-hidden="true"> Plastic Injection Molding</i>
                  <br>
                  <i class="fa fa-cogs" aria-hidden="true"> Assembling</i>
                </div>
              </div>
            </div>
            <div class="column is-half right">
              <div class="box">
                <p class="title">Products</p>
                <div class="content">
                  <i class="fa fa-cogs" aria-hidden="true"> Wolf Claw Pole and Tree Climbing Boot Harness</i>
                  <br>
                  <i class="fa fa-cogs" aria-hidden="true"> Gang Boxes</i>
                  <br>
                  <i class="fa fa-cogs" aria-hidden="true"> Stringer Boxes</i>
                  <br>
                  <i class="fa fa-cogs" aria-hidden="true"> Non-Metallic Scrappers</i>
                </div>
              </div>
            </div>
          </div>
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
.hero {
  background-color: #ECF0F1;
}
h1 {
  font-size: 40px;
  text-align: center;
}
.ep-info {
  font-size: 20px;
  padding: 0 30px
}
.left {
  margin-right: 1px;
}
.right {
  margin-left: 1px;
}
.content {
  text-align: left;
  font-size: 15px;
}
</style>
