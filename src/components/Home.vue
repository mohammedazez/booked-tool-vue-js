<template>

<div>
<Navbar-section></Navbar-section>
<Jumbotron-section></Jumbotron-section>
<Login-section></Login-section>
<Discover-section></Discover-section>
<Touch-section></Touch-section>
</div>

</template>

<script>
import "../styles/Home.scss";
import Navbarsection from "../components/Navbar.vue"
import Jumbotronsection from "../components/Jumbotron.vue"
import Loginsection from "../components/Loginsection.vue"
import Discoversection from "../components/Discover.vue"
import Touchsection from "../components/Touch.vue"

export default {
  name: "Home",
  components: {
    "Navbar-section": Navbarsection,
    "Jumbotron-section": Jumbotronsection,
    "Login-section": Loginsection,
    "Discover-section": Discoversection,
    "Touch-section": Touchsection
  }
};
</script>

