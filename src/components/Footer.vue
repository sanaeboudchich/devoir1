<template>
  <div class="footer">
  <div class="containertext-center">
  <a href="#"><i class="fabfa-instagram"></i></a>
  <a href="#"><i class="fabfa-facebook-f"></i></a>
  <a href="#"><i class="fabfa-linkedin-in"></i></a>
  <a href="#"><i class="fabfa-youtube"></i></a>
  <a href="#"><i class="fabfa-twitter"></i></a>
  <div class="rowcontainer">
  <div class="col-md-3text-centerblock_2">
  <h5>Pages</h5>
  <div class="menub">
  <a href="#">Accueil</a>
  <a href="#">Àpropos</a>
  <a href="#">Contact</a>
  </div>
  </div>

  <div class="col-md-3text-centerblock_2">
  <h5>Informations</h5>
  <div class="menub">
    <p>AliyahDev est une agence web de développement d’applications mobiles, des experts en création des pages et d’applications Web et d’applications desktop. Nous aidons à créer des application avec le meilleur rapport qualité-prix.</p>
  </div>
  </div>

  <div class="col-md-3text-center">
  <h5>Contactez-nous</h5>
  <div class="menubblock_2">
  <p><i class="fasfa-phone"></i>0611841626</p>
    <p><i class="fasfa-email"></i>bsanaae@gmail.com</p>
  <p><i class="fasfa-map-marker-alt"></i>8RuedelaFontaine,<br>75011Paris</p>
  </div>
  </div>

  <div class="iconcol-md-3text-centerblock_2">
  <iframe id="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d99180.6332193097!2d125.67207167718999!3d39.02911725842702!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357e02dae64f4337%3A0xd40677e21771aa95!2sPyongyang%2C%20Cor%C3%A9e%20du%20Nord!5e0!3m2!1sfr!2sfr!4v1604565786486!5m2!1sfr!2sfr" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
  </div>
  </div>

  <p>Tous droits réservés©2021</p>


  </div>

  </div>

</template>

<script>
export default {
name: "Footer"
}
</script>

<style scoped>
a {
  color: white;
  font-weight: lighter;
}
p{
  font-weight: lighter;
}

a:hover {
  color: #FECF98;
}

.block_2 {
  padding-bottom: 50px;
}

#map {
  padding: 10px;
  width: 300px;
}

h5 {
  color: #FECF98;
}

.menub {
  display: grid;
}

.fab {
  font-size: 20px;
  color: white;
  margin:10px;
  padding-bottom: 40px;

}

.fas {
  margin-right:7px;
}

.fab:hover{
  color: #FECF98;
}

.footer{
  background-color: #343a40;
  padding-top: 40px;
  padding-bottom: 30px;
  color: white;
}
</style>