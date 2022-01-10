<template>
  <div class="whiteBoxesContainer">
    <div class="whiteBoxGroup">
      <div class="individualBox">
        <img class="boxItem" src="../../assets/calendar-1.svg" alt="" />
        <p class="boxPara">Hastane Randevusu Alın</p>
      </div>

      <div class="individualBox">
        <img class="boxItem" src="../../assets/camera.svg" alt="" />
        <p class="boxPara">Görüntülü Görüşme Randevusu Alın</p>
      </div>
    </div>

    <div class="whiteBoxGroup">
      <div class="individualBox">
        <img class="boxItem" src="../../assets/heart-circle.svg" alt="" />
        <p class="boxPara">Check-Up Başvurusu Yapın</p>
      </div>

      <div class="individualBox">
        <img class="boxItem" src="../../assets/bitcoin-convert.svg" alt="" />
        <p class="boxPara">Tıbbi İkinci Görüş Formu</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.whiteBoxesContainer {
  /* height: 12.5rem; */
  border-bottom: 1px solid #dae9f1;
  width: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* border: 1px solid black; */
  padding: 1em;
}
.whiteBoxGroup {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: flex-end;
  /* border: 1px solid black; */
  width: 100%;
}
.individualBox {
  /* border: 1px solid black; */
  width: 210px;
  height: 130px;
  background: #ffffff;
  box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.03);
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 1em;
  padding-right: 0;
  /* this makes the text looks better */
  padding-right: 2em;
  margin-bottom: 1.5em;
}
@media only screen and (max-width: 770px) {
  .whiteBoxGroup {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
  }
  .individualBox {
    width: 70%;
    height: 130px;
    background: #ffffff;
    box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.03);
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    padding: 1em;
    padding-right: 0;
    padding-right: 2em;
    margin-bottom: 1.5em;
  }
}

.boxItem {
  margin-bottom: 0.8em;
}
.boxPara {
  width: auto;
  height: auto;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 16px;
  line-height: 20px;
  /* or 125% */
  font-weight: 900;
  text-align: left;
  color: #0a67ad;
}
</style>
