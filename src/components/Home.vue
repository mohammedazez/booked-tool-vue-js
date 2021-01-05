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

<section class="about-area" id="login">
  <div class="text-part">
    <h1>
      Login</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. A aliquid atque commodi dolor est nobis veniam! Eius rerum, unde. Accusamus corporis esse eveniet exercitationem fugiat harum pariatur sequi similique tenetur vitae. Aliquam amet est excepturi, exercitationem facere fugit ipsa laborum molestiae nemo officiis placeat quos repellat saepe temporibus voluptatum.</p>
  </div>
</section>

<section class="port-area" id="discover">
  <div class="text-part">
    <h1>
      Discover</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. A aliquid atque commodi dolor est nobis veniam! Eius rerum, unde. Accusamus corporis esse eveniet exercitationem fugiat harum pariatur sequi similique tenetur vitae. Aliquam amet est excepturi, exercitationem facere fugit ipsa laborum molestiae nemo officiis placeat quos repellat saepe temporibus voluptatum.</p>
  </div>
</section>

<section class="service-area" id="touch">
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

<style scoped>
html {
  scroll-behavior: smooth;
}
.banner-area {
  position: relative;
  background-image: url(https://i.postimg.cc/GtRM7mdX/1.jpg);
  width: 100%;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
}

.about-area,
.port-area,
.service-area,
.contact-area {
  position: relative;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: row;
  width: 100%;
  height: 700px;
}
.text-part {
  width: 65%;
  height: 80%;
}
.about-area {
  background-color: #fefefe;
}
.port-area {
  background-color: #262626;
  color: #fff;
}
.service-area {
  background-color: #fefefe;
}
.contact-area {
  background-color: #262626;
  color: #fff;
}

.navbooked {
  height: 50px;
  width: 100%;
  background-color: #4d4d4d;
  position: relative;
}

.navbooked > .navbooked-header {
  display: inline;
}

.navbooked > .navbooked-header > .navbooked-title {
  display: inline-block;
  font-size: 22px;
  color: #fff;
  padding: 10px 10px 10px 10px;
}

.navbooked > .navbooked-btn {
  display: none;
}

.navbooked > .navbooked-links {
  display: inline;
  float: right;
  font-size: 18px;
}

.navbooked > .navbooked-links > a {
  display: inline-block;
  padding: 13px 10px 13px 10px;
  text-decoration: none;
  color: #efefef;
}

.navbooked > .navbooked-links > a:hover {
  background-color: rgba(0, 0, 0, 0.3);
}

.navbooked > #navbooked-check {
  display: none;
}

@media (max-width:600px) {
  .navbooked > .navbooked-btn {
    display: inline-block;
    position: absolute;
    right: 0px;
    top: 0px;
  }
  .navbooked > .navbooked-btn > label {
    display: inline-block;
    width: 50px;
    height: 50px;
    padding: 13px;
  }
  .navbooked > .navbooked-btn > label:hover,.navbooked  #navbooked-check:checked ~ .navbooked-btn > label {
    background-color: rgba(0, 0, 0, 0.3);
  }
  .navbooked > .navbooked-btn > label > span {
    display: block;
    width: 25px;
    height: 10px;
    border-top: 2px solid #eee;
  }
  .navbooked > .navbooked-links {
    position: absolute;
    display: block;
    width: 100%;
    background-color: #333;
    height: 0px;
    transition: all 0.3s ease-in;
    overflow-y: hidden;
    top: 50px;
    left: 0px;
  }
  .navbooked > .navbooked-links > a {
    display: block;
    width: 100%;
  }
  .navbooked > #navbooked-check:not(:checked) ~ .navbooked-links {
    height: 0px;
  }
  .navbooked > #navbooked-check:checked ~ .navbooked-links {
    height: calc(100vh - 50px);
    overflow-y: auto;
  }
}
</style>
