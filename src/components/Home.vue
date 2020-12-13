<template>
  <div class="home">
    <HomeNavbar />
    <HomeTopBody />
    <div id="footer">
      <HomeFooter />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeNavbar from "./HomeNavbar";
import HomeTopBody from "./HomeTopBody";
import HomeFooter from "./HomeFooter";
export default {
  name: "Home",
  components: { HomeNavbar, HomeTopBody, HomeFooter },
};
</script>
