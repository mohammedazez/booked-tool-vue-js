<template>
<div>
<div class="navbar">
  <a class="logo" href="#"> Harsh</a>
  <ul class="nav">
    <li><a href="#home">Home</a></li>
    <li><a href="#discover">Discover</a></li>
    <li><a href="#login">Login</a></li>
    <li><a href="#touch">Touch</a></li>
    <li><a href="#register">Register</a></li>
    <li><a href="#search">search</a></li>
  </ul>
</div>
</div>
</template>

<script>
export default {
    name: 'Navbar',
    data: []
}

</script>

<style scoped>
html {
  scroll-behavior: smooth;
}
body {
  margin: 0;
  padding: 0;
  font-family: Poppins;
}
h1 {
  font-size: 50px;
  font-family: Audiowide;
}
p {
  font-size: 24px;
  line-height: 50px;
}
.navbar {
  position: fixed;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  flex-wrap: wrap;
  background-color: #d4d7de;
  width: 100%;
  height: 70px;
  z-index: 1;
}
.nav {
  display: flex;
  justify-content: right;
  list-style: none;
  margin-right: 15%;
}
</style>
