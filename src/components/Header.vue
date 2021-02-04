<template>
<div id="hdr">

  <b-navbar toggleable="lg" type="light" variant="light">
    <b-navbar-brand><img src="https://usercontent.aftership.com/2f/ff/2fff341a295164da8ae476843e4540160a97cbd9/track/1563902388521/logo.png" height="100px"></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item active href="#hw">Accueil</b-nav-item>
        <b-nav-item active href="#Apropos">Apropos</b-nav-item>
        <b-nav-item active href="#nps">Nos cervices</b-nav-item>
        <b-nav-item active href="#avis">teams</b-nav-item>
        <b-nav-item active href="#blg">Blog</b-nav-item>
        <b-nav-item active href="#logo">Contactez-Nous</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.navbar{
  position: fixed;
  width: 100%;
  z-index: 564;
  height: 90px;
}


</style>