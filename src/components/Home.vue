<template>
  <div class="home">
    <header>
      <div class="postit">
        <a href="../assets/CV-Clea-Le-Roux.pdf" download>
          <h3>Télécharger mon CV !</h3>
          <p>Format PDF</p>
        </a>
      </div>

      <div class="presentation">
        <h1>Cléa Le Roux</h1>
        <h2>Developeur Web</h2>
      </div>
    </header>

    <div class="body">
      <Ocr/>
    </div>
  </div>
</template>

<script>
import Ocr from './Ocr.vue'

export default {
  name: 'Home',
  components:{
    Ocr,
  },

  props: {
  }
}
</script>

<style lang="scss" scoped>
header
{
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-top: 2%;
}
.postit a {
  text-decoration:none;
  color:#000;
  background:#FFFFA5;
  display:block;
  height:150px;
  width:150px;
  padding:18px;
  
  -webkit-transform: rotate(-6deg);
  -o-transform: rotate(-6deg);
  -moz-transform:rotate(-6deg);  
  
  -moz-transition:-moz-transform .4s ease-in-out;
  -o-transition:-o-transform .4s ease-in-out;
  -webkit-transition:-webkit-transform .4s ease-in-out;

  &:hover, &:focus {
    -webkit-transform: scale(1.25);
    -moz-transform: scale(1.25);
    -o-transform: scale(1.25);
    position:relative;
    z-index:5;
  }
}

.presentation {
  width: 30%;
  text-align: center;
  color: white;
  padding-top: 3%;
  padding-bottom: 3%;
  background-image: url("../assets/trait.png");
  background-position: center;
  background-size: 100%;
  background-repeat: no-repeat;
}
</style>
