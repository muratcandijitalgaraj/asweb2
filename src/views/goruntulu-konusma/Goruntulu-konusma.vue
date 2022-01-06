<template>
  <div id="goruntulu-konusma">
    <!-- desktop -->

    <!-- <div v-responsive.xl><Desktop /></div>

    <div v-responsive.md.lg>Visible on tablet and small laptops ☺</div>

    <div v-responsive.sm.xs>Only visible on smartphone!</div> -->

    <Desktop />
  </div>
</template>

<script>
import Desktop from "./Desktop.vue";
export default {
  components: { Desktop },
};
</script>

<style scoped></style>
