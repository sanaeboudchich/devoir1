<template>
  <div class="newslettercontainer-fluid">
  <div class="container">
  <div class="row">
  <div class="col-md-6">

  <h1>Inscrivez-vous à la newsletter</h1>
  <h4>L’ESSENTIEL À SAVOIR,YCOMPRIS LES DERNIÈRES RECOMMANDATIONS</h4>
  <p>On vous propose de vous abonner à la newsletter a fin de recevoir directement tout ce qu’il faut reteniret toutes les dernières recommandations pour vous aider à mieux </p>
  <form>
    <div class="emailBox">
    <div class="champ">
    <label class="align-self-star" for="name">Votreprénom</label>
    <input class="form-control" type="text" id="name" name="name" minlength="4" placeholder="Sarah" required>
    </div>
    <div class="champ">
    <label for="emailAddress">Votreadressemail</label><br>
    <input class="form-control" id="emailAddress" type="email" size="30" maxLength="30" required
    placeholder="exemple@poms.com" pattern="[a-zA-Z0-9._-]+@[a-zA-Z0-9._-]+.[a-zA-Z.]{2,15}"
    title="Mercidefourniruniquementuneadressemail">
    </div>

    </div>
    <div class="champ">
    <input class="btnbtn-dark" type="submit" id="valide" value="S'inscrire">
    </div>
  </form>

  </div>

  <div class="col-md-6text-center">
  <img src="data:image/png;base64,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" alt="service-image"/>
  </div>

  </div>
  </div>
  </div>
</template>

<script>
export default {
name: "Service"
}
</script>

<style scoped>
.news{
background-color: #ffda79;
}
.champ{
  padding-top:20px;
}

.newsletter{
  padding-top:70px;
  padding-bottom:70px;
}

img{
  width:100%;
}

label{
  font-size:15px;
  text-align:left!important;

}

h1{
  font-size:40px;
  font-weight:bold;
  text-transform:uppercase;
}

h4{
  font-weight:bold;
  color:#FECF98;
  text-transform:uppercase;
}

</style>