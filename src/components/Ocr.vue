<template>
<div class="ocr">
<div class="row">
  <div class="groupomania">
    <h4>Groupomania</h4>
    <span>Création un réseau social d’entreprise</span>
    <img src="" alt="Miniature Groupomania">
    <ul class="tech">
        <li>Vue.js</li>
        <li>Node.js</li>
        <li>Mysql</li>
    </ul>
  </div>

  <div class="hot">
    <h4>Hot Takes</h4>
    <span>Création d'API REST</span>
    <img src="" alt="Miniature Hot Takes">
    <ul class="tech">
        <li>JavaScript</li>
        <li>MongoDB</li>
    </ul>
  </div>

  <div class="orinoco">
    <h4>Orinoco</h4>
    <span>Construction un site e-commerce</span>
    <img src="" alt="Miniature Orinoco">
    <ul class="tech">
        <li>HTML5</li>
        <li>Sass</li>
        <li>JavaScript</li>
        <li>Bootstrap</li>
        <li>Node.js</li>
    </ul>
  </div>
  </div>
<div class="row">
  <div class="chouette">
    <h4>La chouette agence</h4>
    <span>Optimisation un site web existant</span>
    <img src="" alt="Miniature La chouette agence">
    <ul class="tech">
        <li>HTML5</li>
        <li>CSS</li>
        <li>Connaissance de SEO</li>
    </ul>
  </div>

    <div class="homyfood">
    <h4>Ho My Food !</h4>
    <span>Animations CSS</span>
    <img src="" alt="Miniature Ho My Food !">
    <ul class="tech">
        <li>HTML5</li>
        <li>Sass</li>
    </ul>
  </div>

    <div class="reservia">
    <a href="https://cpasklaire.github.io/CleaLeRoux_2_08062021/">
    <h4>Reservia</h4>
    </a>
    <span>Transformation d'une maquette en site web</span>
    <img src="../assets/reservia.png" alt="Miniature Reservia">
    <ul class="tech">
        <li>HTML5</li>
        <li>CSS</li>
    </ul>
  </div>
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
.ocr {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    width: 100%;
    .row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: row;        
    }
}
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
    img {
        width: 100px;
    }
}
.hot {
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
.orinoco {
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
.chouette {
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
.homyfood {
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
.reservia {
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
        img {
        width: 40%;
    }
}
</style>