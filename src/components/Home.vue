<template>
  <div class="home">
    <header>
    <div>
    <a href="https://github.com/Cpasklaire/Portfolio/blob/main/src/assets/CV-Clea-Le-Roux.pdf" download>
      <h2>A Post-it</h2>
      <p>Buy milk!</p>
    </a>
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

<style scoped>

</style>
