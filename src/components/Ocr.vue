<template>
<div class="ocr">
  <div class="groupomania">
    <h4>Groupomania</h4>
    <span>Création un réseau social d’entreprise</span>
    <img>
    <ul class="tech">
        <li>Vue.js</li>
        <li>Node.js</li>
        <li>Mysql</li>
    </ul>
  </div>

  <div class="hot">
    <h4>Hot Takes</h4>
    <span>Création d'API REST</span>
    <img>
    <ul class="tech">
        <li>JavaScript</li>
        <li>MongoDB</li>
    </ul>
  </div>

  <div class="orinoco">
    <h4>Orinoco</h4>
    <span>Construction un site e-commerce</span>
    <img>
    <ul class="tech">
        <li>HTML5</li>
        <li>Sass</li>
        <li>JavaScript</li>
        <li>Bootstrap</li>
        <li>Node.js</li>
    </ul>
  </div>

  <div class="chouette">
    <h4>La chouette agence</h4>
    <span>Optimisation un site web existant</span>
    <img>
    <ul class="tech">
        <li>HTML5</li>
        <li>CSS</li>
        <li>Connaissance de SEO</li>
    </ul>
  </div>

    <div class="homyfood">
    <h4>Ho My Food !</h4>
    <span>Animations CSS</span>
    <img>
    <ul class="tech">
        <li>HTML5</li>
        <li>Sass</li>
    </ul>
  </div>

    <div class="reservia">
    <h4>Reservia</h4>
    <span>Transformation d'une maquette en site web</span>
    <img>
    <ul class="tech">
        <li>HTML5</li>
        <li>CSS</li>
    </ul>
  </div>
</div>
</template>

<script>
export default {
  name: 'Ocr',
  props: {
  }
}
</script>

<style lang="scss" scoped>
.groupomania {
    h4 {
        color: white;
        text-align: center;
        padding-top: 10%;
        padding-bottom: 10%;
        background-image: url("../assets/trait2.png");
        background-position: center;
        background-size: 30%;
        background-repeat: no-repeat;
    }
}
.hot {
    h4 {
        background-image: url("../assets/trait3.png");
        background-position: center;
        background-size: 100%;
        background-repeat: no-repeat;
    }
}
.orinoco {
    h4 {
        background-image: url("../assets/trait4.png");
        background-position: center;
        background-size: 100%;
        background-repeat: no-repeat;
    }
}
.chouette {
    h4 {
        background-image: url("../assets/trait3.png");
        background-position: center;
        background-size: 100%;
        background-repeat: no-repeat;
    }
}
.homyfood {
    h4 {
        background-image: url("../assets/trait2.png");
        background-position: center;
        background-size: 100%;
        background-repeat: no-repeat;
    }
}
.reservia {
    h4 {
        background-image: url("../assets/trait4.png");
        background-position: center;
        background-size: 100%;
        background-repeat: no-repeat;
    }
}
</style>