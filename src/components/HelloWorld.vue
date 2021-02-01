<template>
  <div class="hello">
    <div class="banner_image">
      <div class="tab">
      <H1> cuisiner vous semblent difficile? </H1>
    <h5> découverez notre cômpagnie pour plus de recette et moins de fatigue</h5>
      <br/>
      <br/>

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
.footer{
  width: 100%;
  text-align: center;
  background: #444444;
  padding: 20px 0;
}

.footer{
  height: 80px;
}






h1 {
  color: #FFFFFF;
  text-transform: uppercase;
  left: 180px;
}
.banner_image{
  background: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3DodrXgATaswcpxIjiISNkC5bnMxPJDwnkw&usqp=CAU") no-repeat top ;
  background-size: 900px;
  width: 100%;
  height: 200px;
  display: grid;
  justify-content: center;
  align-items: last;

}
.tab{
 position: -webkit-sticky;
  justify-content: space-around;
}
.navbar{
  width: 100%;
  height: 65px;
  position: absolute;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

</style>
