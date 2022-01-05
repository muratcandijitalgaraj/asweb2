<template>
  <div class="goruntulu-konusma-desktop">
    <div class="outerBox">
      <div class="header">
        <img class="logo" src="../../assets/logo.svg" alt="" />
        <img
          class="onlineIslemler"
          src="../../assets/online-islemler.svg"
          alt=""
        />
        <div class="bulutlar">
          <img class="sol-bulut" src="../../assets/sol-bulut.svg" alt="" />
          <img class="sağ-bulut" src="../../assets/sağ-bulut.svg" alt="" />
        </div>
      </div>
      <div class="greyBox">
        <!-- sideBar -->
        <div class="greyBoxLeft">
          <div class="userContainer">
            <div class="user">
              <img src="../../assets/user.svg" alt="" />
              <div class="userTexts">
                <p class="userName">Mehmet Yılmazer</p>
                <p class="userProtocol">Protokol No: 292390</p>
              </div>
            </div>
          </div>
          <!-- left menu -->
          <Menu />
        </div>
        <div class="greyBoxRight">
          <div class="greyBoxRightUp">
            <WhiteBoxes />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Menu from "./Menu.vue";
import WhiteBoxes from "./WhiteBoxes.vue";
export default { components: { Menu, WhiteBoxes } };
</script>

<style scoped>
.goruntulu-konusma-desktop {
  background: #32a5df;
  height: 100vh;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.outerBox {
  /* border: 1px solid black; */
  height: 100%;
  width: 65%;
}
.header {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
}
.logo {
  margin-right: 2em;
}
.bulutlar {
  margin-left: 4em;
  width: 421px;
  /* original was 217 */
  height: 100%;
  background: linear-gradient(
      180deg,
      #33a5df 16.85%,
      rgba(51, 165, 223, 0) 58.86%
    ),
    url("../../assets/bulut.svg");
  background-repeat: no-repeat;
  /* border: 1px solid black; */
  display: flex;
  flex-direction: row;
  justify-content: space-between;

  /* border: 1px solid red; */
}
.sol-bulut {
  margin: 0;
  padding: 0;
  width: 66px;
  height: 111px;
  background: linear-gradient(90deg, #32a5df 0%, rgba(50, 165, 223, 0) 100%);
}
.sağ-bulut {
  /* width: 66px;
  height: 111px;
  background: linear-gradient(90deg, #32a5df 0%, rgba(50, 165, 223, 0) 100%);
  transform: matrix(-1, 0, 0, 1, 0, 0); */
}
.greyBox {
  /* border: 3px solid red; */
  height: 80%;
  background: #f2f8fb;
  border-radius: 2%;
  display: flex;
  flex-direction: row;
}
.greyBoxLeft {
  border-right: 1px solid #dae9f1;
  width: 30%;
  height: 100%;
}
.userContainer {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  height: 30%;
}
.user {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 2em;
  padding-bottom: 2em;
  border-bottom: 1px solid #dae9f1;
  width: 90%;
  height: 100%;
}

.userTexts {
  padding: 0;
  /* border: 1px solid black; */
}
.userName {
  width: 119px;
  height: 25%;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  line-height: 20px;

  color: #3c4e69;
  padding: 0;
  margin: 0;
  margin-top: 1.5em;
  margin-bottom: 5px;
}
.userProtocol {
  /* Protokol No: 292390 */
  width: 123px;
  height: 18px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 18px;
  /* identical to box height */
  padding: 0;
  margin: 0;
  color: #3c4e69;
}
.greyBoxRight {
  height: 100%;
  width: 100%;
  border: 1px solid black;
}

.greyBoxRightUp {
  /* border: 1px solid black; */
  /* padding-bottom: 2em; */
  /* border-bottom: 1px solid #dae9f1; */
  width: 90%;
  height: 30%;
}
</style>
