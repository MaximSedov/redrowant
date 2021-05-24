<template>
  <Header />
  <Capacity />
  <Problems />
  <Product />
  <Structure />
</template>
<script>
import Header from './components/header.vue'
import Capacity from './components/capacity.vue'
import Problems from './components/problems.vue'
import Product from './components/product.vue'
import Structure from './components/structure.vue'
export default {
  components: { Header, Capacity, Problems, Product, Structure },
  data() {
    return {}
  }
}
</script>
<style lang="scss">
@font-face {
  font-family: "Futura PT";
  src: url("./assets/fonts/FuturaPT-Bold.eot");
  src: local("Futura PT Bold"), local("FuturaPT-Bold"),
    url("./assets/fonts/FuturaPT-Bold.eot?#iefix") format("embedded-opentype"),
    url("./assets/fonts/FuturaPT-Bold.woff") format("woff"),
    url("./assets/fonts/FuturaPT-Bold.ttf") format("truetype");
  font-weight: bold;
  font-style: normal;
}
@font-face {
  font-family: "Futura PT";
  src: url("./assets/fonts/FuturaPT-Light.eot");
  src: local("Futura PT Light"), local("FuturaPT-Light"),
    url("./assets/fonts/FuturaPT-Light.eot?#iefix") format("embedded-opentype"),
    url("./assets/fonts/FuturaPT-Light.woff") format("woff"),
    url("./assets/fonts/FuturaPT-Light.ttf") format("truetype");
  font-weight: 300;
  font-style: normal;
}
@font-face {
  font-family: "Futura PT";
  src: url("./assets/fonts/FuturaPT-BookObl.eot");
  src: local("Futura PT Book Oblique"), local("FuturaPT-BookObl"),
    url("./assets/fonts/FuturaPT-BookObl.eot?#iefix")
      format("embedded-opentype"),
    url("./assets/fonts/FuturaPT-BookObl.woff") format("woff"),
    url("./assets/fonts/FuturaPT-BookObl.ttf") format("truetype");
  font-weight: normal;
  font-style: italic;
}
@font-face {
  font-family: "Futura PT";
  src: url("./assets/fonts/FuturaPT-Heavy.eot");
  src: local("Futura PT Heavy"), local("FuturaPT-Heavy"),
    url("./assets/fonts/FuturaPT-Heavy.eot?#iefix") format("embedded-opentype"),
    url("./assets/fonts/FuturaPT-Heavy.woff") format("woff"),
    url("./assets/fonts/FuturaPT-Heavy.ttf") format("truetype");
  font-weight: 900;
  font-style: normal;
}

@font-face {
  font-family: "Futura PT";
  src: url("./assets/fonts/FuturaPT-Medium.eot");
  src: local("Futura PT Medium"), local("FuturaPT-Medium"),
    url("./assets/fonts/FuturaPT-Medium.eot?#iefix") format("embedded-opentype"),
    url("./assets/fonts/FuturaPT-Medium.woff") format("woff"),
    url("./assets/fonts/FuturaPT-Medium.ttf") format("truetype");
  font-weight: 500;
  font-style: normal;
}
* {
  margin: 0;
  padding: 0;
}
#app {
  overflow: hidden;
  font-family: Futura PT, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
