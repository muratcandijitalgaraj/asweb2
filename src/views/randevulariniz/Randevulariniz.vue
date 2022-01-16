<template>
  <div id="randevulariniz-component">
    <div class="logoPart">
      <div class="logo">
        <img src="../../assets/giris/logo.svg" alt="Anadolu Logo" />
      </div>
      <div class="online-islemler">ONLINE İŞLEMLER</div>
      <div class="bulutlar">
        <div class="sol-bulut"></div>
        <div class="sag-bulut"></div>
      </div>
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
  background-repeat: no-repeat;
  color: #ffffff;
}
.bulutlar {
  width: 421px;
  height: 100%;
  /* border: 1px solid black; */

  background: linear-gradient(
      180deg,
      #33a5df 16.85%,
      rgba(51, 165, 223, 0) 58.86%
    ),
    url("../../assets/bulut.svg");
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.sol-bulut {
  width: 66px;
  height: 111px;

  background: linear-gradient(90deg, #32a5df 0%, rgba(50, 165, 223, 0) 100%);
}

.greyBox {
  width: 1250px;
  height: 1035px;
  background: #f2f8fb;
  border-radius: 22px;
  /* background: black; */
}
</style>
