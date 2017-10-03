<template>
  <div class="home-page">
    <section class="hero is-small">
      <div class="hero-body">
        <div class="container">
          <h1>Welcome To Exacta Plastics</h1>
          <img src="../assets/gears.jpg" alt="mechanical gears">
          <div>
            <br>
            <p class="ep-info">
              Exacta Plastics, Inc. serves their customers in USA and abroad with it's complete plastic injection molding and mold making capabilities in Southern California. To be competitive in mold making we also have our mold making facility offshore in India.
            </p>
            <br>
            <p class="ep-info">
              Exacta Plastics, Inc. also performs secondary operations like assembly and machining for their customers.
            </p>
            <br>
            <p class="ep-info">
              Since 1973, Exacta Plastics, Inc. has been a valued partner to their customers in the fields of Medical Devices, Defense, Power Tools and Commercial Applications. We help customers identify appropriate resin for their application and help them through design and developmental phase. Exacta Plastics, Inc. has a 75 to 400 tons of molding machine range.
            </p>
            <br>
          </div>
          <div class="tile is-ancestor">
            <div class="tile is-6 is-vertical is-parent">
              <div class="tile is-child box">
                <p class="title">
                  <i class="fa fa-phone-square fa-1x" aria-hidden="true"><p></p>+1 (818) 768-1234</i>
                </p>
              </div>
              <div class="tile is-child box">
                <p class="title">
                  <i class="fa fa-map-marker fa-1x" aria-hidden="true"><p></p>137 N. Joy St. Corona, CA 92879</i>
                </p>
              </div>
            </div>
            <div class="tile is-parent">
              <div class="tile is-child box">
                <p class="title">
                  Address
                </p>
                <div class="content">
                  <img class="map" src="../assets/EP-Corona-MAP.png" alt="Address">
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
 .ep-info {
   font-size: 20px;
   padding: 0 30px
 }
 .hero {
   background-color: #ECF0F1;
 }
 .phone {
   font-size: 55px;
 }
 .is-ancestor {
   border-radius: 10px;
   background-color: #09014C;
   text-align: center;
 }
 .is-child {
   background-color: #ECF0F1;
 }
 .map {
   width: 80%;
 }
 .title {
   color: #09014C;
 }
 i {
   padding-top: 70px;
   color: #09014C;
 }
</style>
