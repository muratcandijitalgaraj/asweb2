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
    <div class="greyBox">
      <Menu />
    </div>
  </div>
</template>

<script>
import Menu from "./Menu.vue";
export default {
  components: {
    Menu,
  },
};
</script>

<style scoped>
#randevulariniz-component {
  width: 1920px;
  height: 1264px;
  background: #32a5df;
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  align-items: center;
}
.logoPart {
  width: 1250px;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  /* border: 1px solid black; */
  margin-top: 1.75rem;
}
.logo {
  margin-right: 2.438rem;
}
.online-islemler {
  margin-right: 5.75rem;
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
.sag-bulut {
  width: 66px;
  height: 111px;
  background: linear-gradient(90deg, #32a5df 0%, rgba(50, 165, 223, 0) 100%);
  transform: matrix(-1, 0, 0, 1, 0, 0);
}

.greyBox {
  width: 1250px;
  height: 1035px;
  background: #f2f8fb;
  border-radius: 22px;
  /* background: black; */
}
</style>
