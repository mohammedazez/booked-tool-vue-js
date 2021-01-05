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
    </div>
</template>

<script>
import "../styles/Navbar.scss"

export default {
    name: "Navbarsection"
}
</script>