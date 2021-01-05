<template>
<div>
<!-- Navbar -->
<div class="navbooked">
  <input type="checkbox" id="navbooked-check">
  <div class="navbooked-header">
    <div class="navbooked-title">
      Booked Tool
    </div>
  </div>
  <div class="navbooked-btn">
    <label for="navbooked-check">
      <span></span>
      <span></span>
      <span></span>
    </label>
  </div>
  
  <div class="navbooked-links">
    <a href="#home">Home</a>
    <a href="#discover">Discover</a>
    <a href="#touch">Touch</a>
    <a href="#register">Register</a>
    <a href="#login">Login</a>
    <a href="#search">Search</a>
  </div>
</div>
<!-- End Navbar -->

<section class="banner-area" id="home">
</section>


<!-- Login Area -->
<section class="login-area" id="login" >
  <div class="text-part">
<div class="container-login-area-first">
  <div class="login-grid-one">
    <p class="text-login-area-one" >Please log in to start using</p>
    <h1 class="text-login-area-two">Booked Tool</h1>
  </div>
  <div class="login-grid-two">
     <form>
      <div class="container-login-area">
      <input class="input-login-area" type="text" name="" placeholder="Email" >
      <input class="input-login-area" type="password" name="" placeholder="Password">
      <input class="button-login-area" type="submit" name="" value="Login">
      </div>
    </form>
  </div>
</div>
  </div>
</section>
<!-- End Login Area -->

<!-- Discover -->
<section class="discover-area" id="discover">
  <div class="text-part">
    <h1>Discover</h1>
    <p>Booked Tool.</p>
  </div>
</section>
<!-- End Discover -->

<!-- Touch -->
<section class="touch-area" id="touch">
  <div class="text-part">
    <h1>Get in Touch</h1>
    <p>Want to get in touch? We'd love to her from you. Here's how you can reach us..</p>
  </div>
</section>
<!-- End Touch -->

</div>
</template>

<script>
import "../styles/Home.scss";

export default {
  name: "Home",
  props: {
    msg: String,
  },
};

</script>

