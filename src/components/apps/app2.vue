<template>
  <div class="app1-container">
    <div class="app1top">
      <div class="app1topPart1">
        <a href="https://todoo1-1.herokuapp.com/">
          <img
            src="./todoapplogo.png"
            alt=""
            height="120px"
            width="120px"
            style="border-radius:50%"
        /></a>
      </div>
      <div class="app1topPart2">
        <h2>Todo-APP</h2>

        <div class="app1topPart1btn1">
          Free
        </div>
        <a href="https://todoo1-1.herokuapp.com/">
          <i
            id="icon-globe"
            class="fas fa-globe fa-lg"
            style="color:rgb(117,117,117)"
          ></i
        ></a>
      </div>
    </div>
    <div class="app1body">
      <p class="para1-app1">
        A pesistent Todo-App that uses restful api with long polling method.
      </p>
    </div>
    <div class="app1foo">
      <h3 class="TechUsed">Technologies Used</h3>
      <div class="logo-container">
        <a href="https://firebase.google.com/">
          <img
            style="border-radius:50%"
            src="./expresslogo.png"
            height="30px"
            alt="firebase"
          />
        </a>
        <a href="https://vuejs.org/">
          <img src="./vuelogo.png" height="30px" alt="vuejs" />
        </a>
        <a href="https://vuejs.org/">
          <img src="./mongologo.png" height="40px" alt="vuejs" />
        </a>
        <img src="./csslogo.png" height="30px" alt="" />
        <img src="./htmllogo.png" height="30px" alt="" />
        <a href="https://dashboard.heroku.com/">
          <img src="./herokulogo.jpg" height="30px" alt="" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app2",
};
</script>

<style scoped>
#icon-globe {
  margin-top: 10px;
}
.TechUsed {
  margin-top: 2rem;
}

.app1topPart1btn1 {
  font-size: 16px;
  color: aliceblue;
  text-align: center;
  background-color: rgb(33, 150, 243);
  padding: 1px 2px;
  border-radius: 10px;
  width: 50px;
}
.app1topPart2 {
  padding: 1rem 1rem;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}
.app1top {
  display: flex;
}

.app1-container {
  padding: 1rem 1rem;
  height: 20rem;
  width: 20rem;
  border: 2px solid #e1e1e1;
  border-radius: 5px;
  font-family: "Source Sans Pro", sans-serif;
}

.para1-app1 {
  color: rgb(117, 117, 117);
  margin: 15px 5px;
}
.app1foo {
  color: rgb(117, 117, 117);
}

.logo-container {
  margin-top: 15px;
  display: flex;
  justify-content: space-evenly;
}
</style>
