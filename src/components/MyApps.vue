<template>
  <div class="MyApps-container">
    <div class="tier1">
      <div class="ap1"><app1 /></div>
      <div class="ap2"><app2 /></div>
      <div class="ap3"><app3 /></div>
    </div>
    <!--
    <div class="tier2">
      <app4 />
      <app5 />
      <app6 />
    </div>
    -->
  </div>
</template>

<script>
import app1 from "./apps/app1";
import app2 from "./apps/app2";
import app3 from "./apps/app3";
//import app4 from "./apps/app4";
//import app5 from "./apps/app5";
//import app6 from "./apps/app6";
export default {
  name: "MyApps",
  components: { app1, app2, app3 },
};
</script>

<style scoped>
.MyApps-container {
  margin-top: 3rem;
}
.tier1,
.tier2 {
  display: flex;
  margin-bottom: 2rem;
  justify-content: space-evenly;
}

.ap1:hover,
.ap2:hover,
.ap3:hover {
  /* Start the shake animation and make the animation last for 0.5 seconds */
  animation: shake 0.5s;

  /* When the animation is finished, start again */
  animation-iteration-count: 1s;
}

@keyframes shake {
  0% {
    transform: translate(1px, 1px) rotate(0deg);
  }
  10% {
    transform: translate(-1px, -2px) rotate(-1deg);
  }
  20% {
    transform: translate(-3px, 0px) rotate(1deg);
  }
  30% {
    transform: translate(3px, 2px) rotate(0deg);
  }
  40% {
    transform: translate(1px, -1px) rotate(1deg);
  }
  50% {
    transform: translate(-1px, 2px) rotate(-1deg);
  }
  60% {
    transform: translate(-3px, 1px) rotate(0deg);
  }
  70% {
    transform: translate(3px, 1px) rotate(-1deg);
  }
  80% {
    transform: translate(-1px, -1px) rotate(1deg);
  }
  90% {
    transform: translate(1px, 2px) rotate(0deg);
  }
  100% {
    transform: translate(1px, -2px) rotate(-1deg);
  }
}
</style>
