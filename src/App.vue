<template>
  <the-header></the-header>
  <router-view v-slot="slotProps">
    <transition name="route" mode="out-in">
      <component :is="slotProps.Component"></component>
    </transition>
  </router-view>
</template>

<script>
import { RouterLink, RouterView } from "vue-router";
import TheHeader from "./components/ui/TheHeader.vue";

export default {
  components: {
    TheHeader,
  },
};
</script>
