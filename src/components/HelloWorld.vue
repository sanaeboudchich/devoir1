<template>

  <div class="hed" id="hw">
    <div class="layer">
      <div class="texte_centrer">
        <div class="h1 text-white hh">
          Oh My Case!
        </div>
        <div class="h4 pt-4 text-white hhh">
          <p>Envie de personalisé sa coque?<br> Bienvenu chez nous</p>

        </div>
        <b-button variant="warning" href="#Apropos" class="btn btn-warning mr-2">Decouvrez OMC</b-button>
        <b-button variant="blue" href="#blog" class="btn btn-warning mr-2">Contactze-nous</b-button>

      </div>
    </div>

  </div>


</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hh{
  font-family: 'Hachi Maru Pop', cursive;
}
.hhh{
  font-family: 'Ubuntu', sans-serif;
}
.hed{
  background-image: url("https://i.ibb.co/M83gCjc/moudou-2.png");
  height: 500px;
  padding-top: 90px;
}
.layer {
  background-color: #f34e5e5c;
  position: absolute;
  left: 0;
  width: 100%;
  height: 412px;
  top: 90px;
}

.texte_centrer {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}


</style>
