<template>
  <div id="randevulariniz-component">
    <div class="logoPart">
      <div class="logo">
        <img src="../../assets/giris/logo.svg" alt="Anadolu Logo" />
      </div>
      <div class="online-islemler">ONLINE İŞLEMLER</div>
      <div class="bulutlar"></div>
    </div>
    <div class="greyBox"></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#randevulariniz-component {
  width: 1920px;
  height: 1264px;
  background: #32a5df;
}
.logoPart {
  display: flex;
  flex-direction: row;
  /* border: 1px solid black; */
}
.online-islemler {
  width: 152px;
  height: 18px;

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 17px;
  line-height: 18px;
  /* identical to box height, or 106% */

  text-align: center;

  color: #ffffff;
}
.greyBox {
  width: 1250px;
  height: 1035px;
  /* background: #f2f8fb; */
  border-radius: 22px;
  background: black;
}
</style>
