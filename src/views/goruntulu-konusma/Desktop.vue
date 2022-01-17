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
          <div class="greyLineContainer">
            <div class="greyLine"></div>
          </div>

          <!-- left menu -->
          <div class="menuContainer">
            <Menu />
          </div>
        </div>
        <div class="greyBoxRight">
          <div class="greyBoxRightUp">
            <WhiteBoxes />
            <div class="bigGreyLineContainer">
              <div class="bigGreyLine"></div>
            </div>
          </div>
          <div class="bigWhiteBoxContainer">
            <BigWhiteBox />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Menu from "./Menu.vue";
import WhiteBoxes from "./WhiteBoxes.vue";
import BigWhiteBox from "./BigWhiteBox.vue";
export default { components: { Menu, WhiteBoxes, BigWhiteBox } };
</script>

<style scoped>
.goruntulu-konusma-desktop {
  background: #32a5df;
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.greyLineContainer {
  /* display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center; */
  width: 100%;
  margin-right: 2em;
  margin-left: 2em;
}
.bigGreyLineContainer {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 95%;
  margin-right: 2em;
  margin-left: 2em;
}
.greyLine {
  height: 1px;
  width: 80%;
  background-color: #dae9f1;
}
.bigGreyLine {
  height: 1px;
  width: 100%;
  background-color: #dae9f1;
}
.outerBox {
  /* border: 1px solid black; */
  height: 100%;
  width: 78.125rem;
  margin-bottom: 5%;
}
@media screen and (max-width: 1550px) {
  .outerBox {
    /* Apply some styles */
    width: 85%;
  }
  /* .menuContainer{
    border:5px solid red;
      width: 100%;
        height: 100%;


  } */
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
  /* height: 80%;
  background: #f2f8fb;
  border-radius: 2%; */
  width: 100%;
  /* original 1035px */
  height: 100%;
  background: #f2f8fb;
  border-radius: 22px;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
z .user {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* margin-top: 2em;
  padding-bottom: 2em; */
  /* border-bottom: 1px solid #dae9f1; */
  width: 90%;
  height: 90%;
  /* border: 1px solid red; */
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
.greyBoxLeft {
  border-right: 1px solid #dae9f1;
  width: 20%;
  height: auto;
  padding-right: 1em;
  /* border:1px solid red; */
}
@media only screen and (max-width: 1200px) {
  .greyBoxLeft {
    width: 25%;
  }
}
.userContainer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 12.5rem;
  /* border: 1px solid black; */
  /* border-bottom: 1px solid #dae9f1; */
}
.greyBoxRight {
  height: 100%;
  width: 80%;
  /* border: 1px solid black; */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.greyBoxRightUp {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 95%;
  height: 12.5rem;
  /* border-bottom: 1px solid #dae9f1; */
}
.bigWhiteBoxContainer {
  height: 100%;
  width: 100%;
}
</style>
