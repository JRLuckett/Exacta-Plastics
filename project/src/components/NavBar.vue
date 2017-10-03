<template>
  <div>
    <div class="columns is-mobile">
      <div class="column is-one-third">
        <img src="../assets/logo.jpg" alt="Exacta-Plastic-Logo" width="224" height="56">
      </div>
      <div @click="setInfo('home')" class="column nav-bar hover">
        Home
      </div>
      <div @click="setInfo('about')" class="column nav-bar hover">
        About
      </div>
      <div @click="setInfo('services')" class="column nav-bar hover">
        Services
      </div>
      <div @click="setInfo('Contact')" class="column nav-bar hover">
        Contact
      </div>
    </div>
    <HomePage v-show="info === 'home'"></HomePage>
    <AboutUs v-show="info === 'about'"></AboutUs>
    <Services v-show="info === 'services'"></Services>
    <Contact v-show="info === 'Contact'"></Contact>
    <footer class="footer">
      <div class="container is-fullhd">
        <div class="columns is-mobile">
          <div class="column is-one-third footer-bar">
            Exacta Plastics, INC.
          </div>
          <div @click="setInfo('home')" class="column footer-bar hover">
            Home
          </div>
          <div @click="setInfo('about')" class="column footer-bar hover">
            About
          </div>
          <div @click="setInfo('services')" class="column footer-bar hover">
            Services
          </div>
          <div @click="setInfo('Contact')" class="column footer-bar hover">
            Contact
          </div>
        </div>
      </div>
    </footer>
    <div class="content has-text-centered">
      © Copyright alphaOneStategy.com 2017
    </div>
  </div>
</template>

<script>
import HomePage from './HomePage.vue'
import AboutUs from './AboutUs.vue'
import Services from './Services.vue'
import Contact from './Contact.vue'
export default {
  components: {
    'HomePage': HomePage,
    'AboutUs': AboutUs,
    'Services': Services,
    'Contact': Contact
  },
  data() {
    return {
      info: 'home'
    }
  },
  methods: {
    setInfo(info) {
      this.info = info
    }
  }
}
</script>

<style scoped>
.columns {
  margin-bottom: -10px;
}
.nav-bar {
  color: #232A53;
  padding-top: 40px;
}
.hover:hover {
  color: #4FF3FC;
}
.footer {
  background-color: #09014C;
  height: 30px;
}
.footer-bar {
  padding-top: 25px;
  color: #ACACAC;
}
</style>
