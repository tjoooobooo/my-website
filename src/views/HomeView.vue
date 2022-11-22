<script>
import LandingPage from "../components/home/LandingPage.vue";

export default {
  components: { LandingPage },
};
</script>

<template>
  <div class="w-screen h-screen snap-y snap-mandatory overflow-scroll">
    <landing-page
      id="landing"
      class="snap-center shrink-0 grid w-screen h-screen"
    ></landing-page>
  </div>
</template>
