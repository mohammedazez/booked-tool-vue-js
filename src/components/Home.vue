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

<section class="login-area" id="login">
  <div class="text-part">
    <p>Please log in start using</p>
    <h1>Booked Tool</h1>
  </div>
</section>

<section class="discover-area" id="discover">
  <div class="text-part">
    <h1>
      Discover</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. A aliquid atque commodi dolor est nobis veniam! Eius rerum, unde. Accusamus corporis esse eveniet exercitationem fugiat harum pariatur sequi similique tenetur vitae. Aliquam amet est excepturi, exercitationem facere fugit ipsa laborum molestiae nemo officiis placeat quos repellat saepe temporibus voluptatum.</p>
  </div>
</section>

<section class="touch-area" id="touch">
  <div class="text-part">
    <h1>
     Get in Touch</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. A aliquid atque commodi dolor est nobis veniam! Eius rerum, unde. Accusamus corporis esse eveniet exercitationem fugiat harum pariatur sequi similique tenetur vitae. Aliquam amet est excepturi, exercitationem facere fugit ipsa laborum molestiae nemo officiis placeat quos repellat saepe temporibus voluptatum.</p>
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


