<template>
  <div id="logo">
    <b-row class="w-100">
      <b-col class="col-sm-6"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRWZFWOtj0mkrhFVzDrlwDYCGbsCYXgT1kPZg&usqp=CAU" height="400" class="w-100" >
      </b-col>
      <b-col class="col-sm-6"><H1> INSCRIVEZ-VOUS À LA NEWSLETTER</H1>
        <p>On vous propose de vous abonner à la newsletter afin de recevoir directement tout ce qu’il faut retenir et toutes les dernières recommandations pour vous aider à mieux</p>
        <form>
          <div class="emailBox">
            <div class="champ">
              <label class="align-self-star" for="name">Votreprénom</label>
              <input class="form-control" type="text" id="name" name="name" minlength="4" placeholder="Sarah" required>
            </div>
            <div class="champ">
              <label for="emailAddress">Votreadressemail</label><br>
              <input class="form-control" id="emailAddress" type="email" size="30" maxLength="30" required
                     placeholder="exemple@ohmycase.com" pattern="[a-zA-Z0-9._-]+@[a-zA-Z0-9._-]+.[a-zA-Z.]{2,15}"
                     title="Mercidefourniruniquementuneadressemail">
            </div>

          </div>
          <br>
          <div>
            <b-button v-b-modal.modal-2>S'incrire</b-button>

            <b-modal id="modal-2" >
              <p class="my-4">Merci pour votre inscription ^^ !</p>
            </b-modal>
          </div>
        </form></b-col>
    </b-row>
    </div>
</template>

<script>
export default {
name: "Logo.vue"
}
</script>

<style scoped>

</style>