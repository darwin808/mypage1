<template>
  <div class="HomeNavbar-container">
    <div class="navHeader">
      <h1 class="darwin">Darwin A.</h1>

      <ul class="nav-links">
        <div class="about">ABOUT</div>
        <div class="work">
          <a href="#footer" style=" text-decoration: none; color:white">WORK</a>
        </div>
        <div class="contact">CONTACT</div>
      </ul>
    </div>
    <div class="HomeNavbarParagrap">
      <p class="para1">Welcome to my page.</p>
      <p class="para2">I make applications.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeNavbar",
};
</script>

<style scoped>
.HomeNavbarParagrap {
  padding: 5rem 25rem;
  display: flex;
  flex-direction: column;
  font-family: Arial, Helvetica, sans-serif;
  color: azure;
}
.HomeNavbarParagrap .para1 {
  font-size: 4rem;
}
.HomeNavbarParagrap .para2 {
  font-size: 2rem;
}

.HomeNavbar-container {
  display: flex;
  flex-direction: column;
  height: 60vh;
  width: 100%;
  background-image: url("/2.jpg");
  background-size: cover;
}

.navHeader {
  display: flex;
  justify-content: space-around;
  font-family: Arial, Helvetica, sans-serif;
  padding: 3rem 5rem;
  color: azure;
}

ul {
  display: flex;
}

.about,
.work,
.contact {
  padding-top: 9px;
  padding-left: 0.5rem;
  padding-right: 0.5rem;
}

.about:hover,
.work:hover,
.contact:hover {
  cursor: pointer;
  background-color: rgb(166, 171, 174);
  border-radius: 2px;
}

.darwin:hover {
  cursor: pointer;
}
</style>
