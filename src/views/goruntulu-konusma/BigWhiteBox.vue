<template>
  <div class="bigWhiteBoxComponent">
    <div class="titlePart">
      <div class="bigTitle">Görüntülü Görüşme Randevusu</div>
      <div class="smallTitle">Geri Dön</div>
    </div>
    <div class="bigWhiteBox">
      <div class="bigWhiteBoxItem">
        <img class="bigWhiteBoxImg" src="../../assets/foto.svg" alt="" />
        <div class="paraContainer">
          <div class="boxTitle">Prof. Dr. Mehmet Balkan</div>
          <div class="boxPara">Anesteziyoloji ve Reanimasyon Birimi</div>
        </div>
      </div>
      <div class="greyLine"></div>

      <div class="bigWhiteBoxItem">
        <img
          class="bigWhiteBoxIcon"
          src="../../assets/user-square.svg"
          alt=""
        />
        <div class="paraContainer">
          <div class="boxPara">Kim için</div>
          <div class="boxTitle">Mehmet Balkan</div>
        </div>
      </div>
      <div class="greyLine"></div>
      <div class="itemWithButton">
        <div class="bigWhiteBoxItem">
          <img class="bigWhiteBoxIcon" src="../../assets/hospital.svg" alt="" />
          <div class="paraContainer">
            <div class="boxPara">Hastane</div>
            <div class="boxTitle">Ataşehir Tıp Merkezi</div>
          </div>
        </div>
        <button class="btn">Yol Tarifi Alın</button>
      </div>
      <div class="greyLine"></div>
      <div class="itemWithButton">
        <div class="bigWhiteBoxItem">
          <img
            class="bigWhiteBoxIcon"
            src="../../assets/calendar-grey.svg"
            alt=""
          />
          <div class="paraContainer">
            <div class="boxPara">Tarih</div>
            <div class="boxTitle">20 Ocak 2021 - 15:30</div>
          </div>
        </div>
        <button class="btn">Takvime Ekle</button>
      </div>
      <div class="greyLine"></div>

      <div class="bigWhiteBoxItem">
        <img
          id="sikayetId"
          class="bigWhiteBoxIcon"
          src="../../assets/flash-circle.svg"
          alt=""
        />
        <div class="paraContainer">
          <div class="boxPara">Şikayet</div>
          <div class="boxTitle">
            Gögüs boşlugumda ara ara ağrılar hissediyorum. Lorem ipsum dolor sit
            amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt
            ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
            nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            consequatLorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
            nisi ut aliquip ex ea commodo consequat
          </div>
        </div>
      </div>
      <div class="greyLine"></div>

      <div class="bigWhiteBoxItem">
        <img class="bigWhiteBoxIcon" src="../../assets/slash.svg" alt="" />
        <div class="paraContainer">
          <div class="sikayetPara">Randevuyu İptal Et</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.bigWhiteBoxComponent {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.greyLine {
  height: 1px;
  width: 100%;
  background-color: #e7eff3;
}
.titlePart {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  /* border: 1px solid black; */
  width: 97%;
  padding: 2em;
}
@media only screen and (max-width: 770px) {
  .titlePart {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    /* border: 1px solid black; */
    width: 97%;
    padding: 2em;
  }
}
.bigTitle {
  width: 310px;
  height: 30px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  line-height: 30px;
  /* identical to box height, or 136% */
  letter-spacing: -0.02em;

  color: #3c4e69;
}
.smallTitle {
  width: auto;
  height: 20px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 20px;
  /* identical to box height, or 143% */

  color: #3c4e69;
  margin-top: 3px;
}
.bigWhiteBox {
  /* border: 1px solid black; */
  width: 90%;
  height: 80%;
  background-color: white;
  padding: 0 1.625rem 1.625rem 1.625rem;
  border-radius: 2%;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  margin-bottom: 5em;
}
.itemWithButton {
  width: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  /* border: 1px solid black; */
}
.btn {
  width: 12em;
  height: 39px;
  background: #32a5df;
  color: white;

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 26px;
  /* identical to box height, or 162% */
  text-align: center;
  border-radius: 6px;
  /* transform: matrix(1, 0, 0, -1, 0, 0); */
  margin-top: 10px;
}
.bigWhiteBoxItem {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  /* border: 1px solid black; */
  /*  padding-bottom: 1.5em; */
  margin-bottom: 1.5em;
  margin-top: 1.5em;
}
.paraContainer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  margin-left: 1em;
}
.boxTitle {
  /* width: 169px;
  height: 20px; */
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  line-height: 1.45rem;
  /* border: 1px solid black; */
  padding: 0;
  color: #3c4e69;
  justify-self: flex-start;
  text-align: left;
}
.boxPara {
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 20px;
  /* identical to box height, or 143% */
  /* border: 1px solid black; */

  color: #818b9a;
}
.bigWhiteBoxIcon {
  margin-bottom: 2px;
}
#sikayetId {
  align-self: flex-start;
  padding-top: 10px;
}
.sikayetPara {
  width: 140px;
  height: 26px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 26px;
  /* identical to box height, or 162% */
  text-align: center;

  color: #ff5858;
}
</style>
