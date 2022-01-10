<template>
  <div id="goruntulu-konusma">
    <!-- desktop -->

    <div v-responsive.lg.xl><Desktop /></div>

    <div v-responsive.md><Tablet /></div>

    <div v-responsive.sm.xs><Mobile /></div>
  </div>
</template>

<script>
import Desktop from "./Desktop.vue";
import Tablet from "./Tablet.vue";
import Mobile from "./Mobile.vue";
export default {
  components: { Desktop, Tablet, Mobile },
};
</script>

<style scoped>
#goruntulu-konusma {
  /* background: #32a5df; */
  height: 100%;
  width: 100%;
}
</style>
