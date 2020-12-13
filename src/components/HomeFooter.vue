<template>
  <div class="HomeFooter-container">
    <div class="soscialMediaico">
      <a
        style="color: white;"
        href="https://www.facebook.com/darwin.apolinario"
      >
        <i class="fab fa-facebook-square fa-2x"> </i
      ></a>

      <a style="color: white;" href="https://github.com/darwin808">
        <i class="fab fa-github fa-2x"></i
      ></a>

      <a
        style="color: white;"
        href="https://www.facebook.com/darwin.apolinario"
      >
        <i class="fab fa-google-plus-g fa-2x"></i
      ></a>

      <a
        style="color: white;"
        href="https://www.linkedin.com/in/darwin-apolinario-35b084114/"
      >
        <i class="fab fa-linkedin fa-2x"></i
      ></a>

      <a style="color: white;" href="https://www.instagram.com/darwinnn.nnn/">
        <i class="fab fa-instagram fa-2x"></i>
      </a>
    </div>
    <div class="ecomText"><h3>Copyright © 2020</h3></div>
  </div>
</template>

<script>
//import HomeFooterLower from "./HomeFooterLower";
////import HomeFooterTop from "./HomeFooterTop";
//import HomeFooterBody from "./HomeFooterBody";
export default {
  name: "HomeFooter",
  //components: { HomeFooterLower, HomeFooterTop, HomeFooterBody },
};
</script>

<style scoped>
.HomeFooter-container {
  height: 10%;
  background-color: #434b4e;
  display: flex;
  justify-content: space-between;
  padding: 3% 10%;
  color: white;
}

.soscialMediaico {
  text-decoration: none;
  display: grid;
  grid-template-columns: 50% 50% 50% 50% 50%;
}
</style>
