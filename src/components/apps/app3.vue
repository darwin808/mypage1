<template>
  <div class="app3-container">
    <div class="app3top">
      <div class="app1topPart1">
        <a href="https://vueeeeeeeee.web.app/">
          <img
            src="./ecom2.png"
            alt=""
            height="120px"
            width="120px"
            style="border-radius:50%"
        /></a>
      </div>
      <div class="app3topPart2">
        <h2>Ecommerce Website</h2>

        <div class="app1topPart1btn1">
          Under construction
        </div>
        <a href="https://ecommerce-v10.herokuapp.com/">
          <i
            id="icon-globe"
            class="fas fa-globe fa-lg"
            style="color:rgb(117,117,117)"
          ></i
        ></a>
      </div>
    </div>
    <div class="app3body">
      <p class="para1-app1">
        An ecommerce website that sells fruits powered by Vue,Vuex & Vuetify.
      </p>
    </div>
    <div class="app3foo">
      <h3>Technologies Used</h3>
      <div class="logo-container">
        <a href="https://vuejs.org/">
          <img src="./vuelogo.png" height="30px" alt="vuejs" />
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
  name: "app1",
};
</script>

<style scoped>
#icon-globe {
  margin-top: 10px;
}

.app1topPart1btn1 {
  font-size: 16px;
  color: aliceblue;
  text-align: center;
  background-color: rgb(248, 199, 0);
  padding: 1px 2px;
  border-radius: 10px;
  width: 160px;
}
.app3topPart2 {
  padding: 1rem 1rem;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}
.app3top {
  display: flex;
}

.app3-container {
  padding: 1rem 1rem;
  height: 20rem;
  width: 20rem;

  font-family: "Source Sans Pro", sans-serif;
  border: 2px solid #e1e1e1;
  border-radius: 5px;
}

.para1-app1 {
  color: rgb(117, 117, 117);
  margin: 15px 5px;
}
.app3foo {
  color: rgb(117, 117, 117);
}

.logo-container {
  margin-top: 15px;
  display: flex;
  justify-content: space-evenly;
}
</style>
