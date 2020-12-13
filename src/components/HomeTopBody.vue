<template>
  <div class="HomeTopBody-container">
    <div class="bodycontent">
      <h1>This is me</h1>
      <p class="parabody">
        I enjoy building apps in my free time when I'm not doing much. Looking
        to get into machine learning and trying to automate as many things as
        possible. Love to encourage new coders that they can do it too! I'm not
        very smart, just curious to see how things work. I'm also not that good
        of a writer as you can see. lol. Anyways, you are free to download any
        of the code thats on my github! And I hope you have a great day!.<br /><br />
        Always looking for new clients! Would love to talk to you about your
        idea.
      </p>
    </div>
    <div class="works">
      <h1>My Work</h1>
      <div class="applist">
        <MyApps />
      </div>
    </div>
  </div>
</template>

<script>
import MyApps from "./MyApps";
export default {
  name: "HomeTopBody",
  components: { MyApps },
};
</script>

<style scoped>
.parabody {
  padding: 2rem 0;
}
.HomeTopBody-container {
  display: flex;
  flex-direction: column;
  padding: 3rem 25rem;
}

.bodycontent {
  letter-spacing: 1px;
  font-family: "Source Sans Pro", sans-serif;
  display: flex;
  flex-direction: column;
}
</style>
w
