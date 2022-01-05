<template>
  <div class="whiteBoxesContainer">
    <div class="whiteBoxItem"></div>
    <div class="whiteBoxItem"></div>
    <div class="whiteBoxItem"></div>
    <div class="whiteBoxItem"></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.whiteBoxesContainer {
  height: 100%;
  border-bottom: 1px solid #dae9f1;
  width: 100%;
  /* border: 1px solid black; */
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.whiteBoxItem {
  border: 1px solid black;
  width: 210px;
  height: 130px;
  background: #ffffff;
  box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.03);
  border-radius: 10px;
}
</style>
