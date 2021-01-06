<template>
<nav class="navbar navbar-default navbar-fixed-top navbooked" role="navigation">
  <div class="navbar-header">
    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
    </button>    
  </div>
  <div class="navbar-collapse collapse">
    <ul class="nav navbar-nav navbar-left"> 
        <li><a href="#home"><img class="logo" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609900545/Ice%20Message%20Indonesia/social-media-marketing_pp1kym.png"/></a></li>
    </ul>
    <ul class="nav navbar-nav navbar-right">
      <li><a href="#home">Home</a></li>
      <li><a href="#discover">Discover</a></li>
      <li><a href="#login">Register</a></li>
      <li><a href="#touch"><img class="search-navbar" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1609900545/Ice%20Message%20Indonesia/loupe_kakugz.png"/></a></li>
    </ul>
  </div>
</nav>

    <!-- <div>
        <div class="navbooked">
          <input type="checkbox" id="navbooked-check">
          <div class="navbooked-header">
            <div class="navbooked-title"> 
              <img class="logo" src="https://res.cloudinary.com/dulqd0xea/image/upload/v1608949674/029-transfer_nscany.png"/>
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
    <a class="nav-teks" href="#home">Home</a>
    <a class="nav-teks" href="#discover">Discover</a>
    <a class="nav-teks" href="#login">Register</a>
    <a class="nav-teks" href="#touch">Search</a>
  </div>
</div>
    </div> -->

    
</template>

<script>
import "../styles/Navbar.scss"

export default {
    name: "Navbarsection"
}
</script>