<template>
<div>
<Navbar-section></Navbar-section>
<section class="banner-area" id="home">
</section>

<Login-section></Login-section>


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
import Loginsection from "../components/Loginsection.vue"
import Navbarsection from "../components/Navbar.vue"

export default {
  name: "Home",
  components: {
    "Login-section": Loginsection,
    "Navbar-section": Navbarsection
    // "Navbar-section": Navbar
  }
};


</script>

