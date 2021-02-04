<template>
  <div id="Apropos" class="noserv">
    <b-row  class="w-100">
      <b-col class="col-sm-6"><br>
        <br>
        <h1> Qui somme nous?</h1>
        <p>Nous vous offrons la possibilité de personnaliser votre coque, Grips & Rings et vos pull aussi! Une livraison gratuite partout dans le monde. que voulais vous de plus?</p>
        <br>
        <div>
          <b-button v-b-modal.modal-1>Surprise</b-button>

          <b-modal id="modal-1" >
            <p class="my-4">Vous avez sur 1 articl acheter = 1 ouffer!! et une livraison gratuite partout dans le monde! ^^</p>
          </b-modal>
        </div>
      </b-col>
      <b-col class="col-sm-6"><img src="https://i.pinimg.com/originals/05/60/15/0560156b36ea488742ac9648caab8220.jpg" height="370px" class="rounded p-5 w-100" width="600">
      </b-col>
    </b-row>

  </div>
</template>

<script>
export default {
name: "apropo"
}
</script>

<style scoped>
head {
  scroll-behavior: smooth;
}
.noserv{
  background-color: #f7f1e3;
  height: 400px;


}

</style>