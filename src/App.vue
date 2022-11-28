<template>
  <div id="app" class="bg-light">
    <Navbar />
    <Breadcrumb />
    <Gallery />
    <Slider />
    <Footer />
    <Copyright />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar'
import Breadcrumb from './components/Breadcrumb'
import Gallery from './components/Gallery'
import Slider from './components/Slider'
import Footer from './components/Footer'
import Copyright from './components/Copyright'


export default {
  name: 'App',
  components: {
    Navbar, Breadcrumb, Gallery, Slider, Footer, Copyright
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

.border-rounded {
  border-radius: 20px;
}

.bg-pink {
  background-color: pink;
}

.bg-light {
  background-color: lightgray;
}

.border-pink {
  border: 1px solid pink;
}

div.form {
  width: 40%;
}

.main-img img {
  width: 560px;
}

.desc-img>* {
  margin-bottom: 20px;
}

.desc-img h2 {
  margin-bottom: 5px;
}

.img-5 {
  position: relative;
}

.img-5:after {
  content: '';
  position: absolute;
  left: 0px;
  top: 0px;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
}


.send-email {
  border-radius: 10px;
  overflow: hidden;
}

.input-email {
  border: none;
  padding: 5px 10px;
}

.btn-submit {
  border-radius: 10px;
  border: none;
  background-color: pink;
}

.copyright {
  text-align: center;
}
</style>
