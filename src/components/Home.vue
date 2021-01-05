<template>
<div>
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


<section class="banner-area" id="home">
</section>


<!-- Login Area -->
<section class="login-area" >
  <div class="text-part">
<div>
  <div class="login-grid-one">
    <p class="text-login-area-one">Please log in to start using</p>
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

<section class="discover-area" id="discover">
  <div class="text-part">
    <h1>Discover</h1>
    <p>Booked Tool.</p>
  </div>
</section>

<section class="touch-area" id="touch">
  <div class="text-part">
    <h1>Get in Touch</h1>
    <p>Want to get in touch? We'd love to her from you. Here's how you can reach us..</p>
  </div>
</section>

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

