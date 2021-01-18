<template>
  <div id="app">
     <nav class="navbar navbar-expand-md navbar-dark fixed-top" id="banner">
    <div class="container">
      <!-- Brand -->
      <a class="navbar-brand" href="#"><span>Logo</span>Here</a>
      <!-- Toggler/collapsibe Button -->
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Navbar links -->
      <div class="collapse navbar-collapse" id="collapsibleNavbar">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!--Header_section-->

  <!--Hero_Section-->
  <section id="hero_section" class="top_cont_outer">
    <div class="hero_wrapper">
      <div class="container">
        <div class="hero_section">
          <div class="row">
            <div class="col-md-12">
              <div class="top_left_cont zoomIn wow animated">
                <h2>Welcome to the easy <br> <strong>Life</strong></h2>
                <div class="underline"></div>
                <a href="#service" class="read_more2">Book Now</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!--Hero_Section-->

  <MainSection/>
  <AboutUs/>
  <Footer/>
  </div>
</template>

<script>
import MainSection from './components/MainSection.vue'
import AboutUs from './components/AboutUs.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    MainSection,
    AboutUs,
    Footer
  }
}
</script>

<style>


body {
    font-weight: 400;
    height: 100vh;
      font-family: 'Open Sans',
      sans-serif;
      font-size: 14px;
      font-weight: normal;
      color: #888888;
      margin: 0;
}
h2 {
    font-size: 38px;
    color: #222222;
    font-family: 'Raleway', sans-serif;
    font-weight: normal;
    margin: 0px 0 25px 0;
    text-align: center;
    text-transform: uppercase;
}

h3 {
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
    color: #222222;
    font-size: 18px;
    margin: 0 0 5px 0;
}

h6 {
    font-size: 16px;
    color: #888888;
    font-family: 'Open Sans', sans-serif;
    font-weight: 400;
    text-align: center;
    margin: 0 0 60px 0;
}

p {
    line-height: 24px;
    margin: 0;
}


.navbar-brand span {
    color: #fed136;
    font-size: 25px;
    font-weight: 700;
    letter-spacing: 0.1em;
    font-family: 'Kaushan Script', 'Helvetica Neue', Helvetica, Arial, cursive;
}

.navbar-brand {
    color: #fff;
    font-size: 25px;
    font-family: 'Kaushan Script', 'Helvetica Neue', Helvetica, Arial, cursive;
    font-weight: 700;
    letter-spacing: 0.1em;
}

.navbar-nav .nav-item .nav-link {
    padding: 1.1em 1em !important;
    font-size: 120%;
    font-weight: 500;
    letter-spacing: 1px;
    color: #fff;
    font-family: 'Gothic A1', sans-serif;
}

.navbar-nav .nav-item .nav-link:hover {
    color: #fed136;
}

.navbar-expand-md .navbar-nav .dropdown-menu {
    border-top: 3px solid #fed136;
}

.dropdown-item:hover {
    background-color: #fed136;
    color: #fff;
}

nav {
    -webkit-transition: padding-top .3s, padding-bottom .3s;
    -moz-transition: padding-top .3s, padding-bottom .3s;
    transition: padding-top .3s, padding-bottom .3s;
    border: none;
}

.shrink {
    padding-top: 0;
    padding-bottom: 0;
    background-color: #374045;
}

.wrapper {

    height: 100%;
    width: 80%;
    display: flex;
    justify-content: center;
    
}

.top_cont_outer {
     /* background: #EFB21D ;  */
    position: relative;
    background: url('../src/assets/slide-1.jpg') top center no-repeat;  
    height: 750px;
    width: auto;
}

.hero_section {
    position: relative;
    padding-top: 100px;
}

.white_pad {
    position: relative;
    right: 0px;
    bottom: 0px;
}

.white_pad img {
    position: absolute;
    right: 0px;
    bottom: 0px;
}

.top_left_cont {
    padding: 110px 0;
}

.top_left_cont h3 {
    font-size: 16px;
    color: #f56eab;
    margin: 0 0 20px 0;
    text-align: left;
    font-weight: 700;
}

.top_left_cont h2 {
    font-size: 40px;
    color: #000;
    line-height: 52px;
    margin: 0 0 26px 0;
    font-family: 'Raleway', sans-serif;
    text-align: center;
}

.top_left_cont h2 strong {
    font-weight: 700;
    color: #EFB21D;
}

.top_left_cont p {
    font-size: 20px;
    color: #C3C3C3;
    margin: 0 0 30px 0;
    line-height: 33px;
    text-align: center;
    font-family: sans-serif;
    font-weight: 100;
}
.wrapper {

    height: 100%;
    width: 80%;
    display: flex;
    justify-content: center;
    
}

a.read_more,
a.read_more2 {
    font-family: 'Raleway', sans-serif;
    display: block;
    font-size: 16px;
    width: 178px;
    height: 46px;
    line-height: 46px;
    border-radius: 3px;
    text-align: center;
    text-transform: uppercase;
    font-weight: 600;
    transition: all 0.2s ease-in-out;
    -moz-transition: all 0.2s ease-in-out;
    -webkit-transition: all 0.2s ease-in-out;
    background: #080808;
    color: #fff;
    border: 1px solid #fff;
    margin: 0 auto;
}

a.read_more {
    color: #3C3C3C;
    border: 1px solid #3C3C3C;
}

a.read_more2:hover,
a.read_more:hover {
    background: #fff;
    color: #EFB21D;
    border: 1px solid #fff;
}

a.read_more:hover {
    background: #fff;
    color: #EFB21D;
    border: 1px solid #EFB21D;
}

</style>
