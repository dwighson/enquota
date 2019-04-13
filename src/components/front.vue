<template>
  <div class="front">
    <newstock/>
    <allcollections/>
    <testimonials/>
    <div class="aboutuswrap">
      <aboutus/>
      <instagram/>
    </div>
  </div>
</template>
<script>
import newstock from "./newstock";
import allcollections from "./allcollections";
import testimonials from "./testimonials";
import aboutus from "./aboutus";
import instagram from "./instagram";

export default {
  components: {
    newstock,
    allcollections,
    testimonials,
    aboutus,
    instagram
  }
};
</script>

<style>
.front {
  height: 100vh;
}
.aboutuswrap {
  /* display: flex; */
  text-align: center;
  width: 100%;
  height: 600px;
}
</style>
