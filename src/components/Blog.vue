<template>
<div class="row w-100 m-0" id="blg">
  <div class="col">
    <br>
    <br>
    <br>


    <H1>Venez par là!!</H1>
   <h5>Si vous voulez savoir plus sur nous...</h5>
    <br>
    <b-button variant="success" href="https://www.facebook.com/ohmycaseoff/">Abonnez-vous</b-button>
  </div>
  <div class="col">
    <iframe class="w-100" width="600" height="330" src="https://www.youtube.com/embed/3vfD3EirxEo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
</template>

<script>
export default {
name: "Blog",
  props: {
    msg: String
  }
}
</script>

<style scoped>
.row{
  background-color: #f5cd79;
}

</style>