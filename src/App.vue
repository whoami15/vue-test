<template>
  <div id="app">
     <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand" href="index.html">ladkfjdkfjkfdj</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="/">Home</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
     <header class="masthead" style="background-image: url('@/assets/img/about-bg.jpg')">
    <div class="overlay"></div>
    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-md-10 mx-auto">
          <div class="page-heading">
            <h2>Hello mga Ka-Lockdown</h2>
            <span class="subheading">sana ol</span>
          </div>
        </div>
      </div>
    </div>
  </header>
  </div>
</template>


<script>

export default {
  name: 'App',
  components: {
  },
  created () {
    document.title = "Mga Ka-Lockdown";
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Lora:400,700,400italic,700italic');
@import url('https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800');
@import './assets/css/bootstrap.min.css';
@import './assets/css/clean-blog.min.css';

</style>

<style lang="scss">
$fa-font-path: "~@fortawesome/fontawesome-free/webfonts";
@import "~@fortawesome/fontawesome-free/scss/fontawesome";
@import "~@fortawesome/fontawesome-free/scss/solid"; // fas
@import "~@fortawesome/fontawesome-free/scss/regular"; // far
@import "~@fortawesome/fontawesome-free/scss/brands"; // fab
</style>
