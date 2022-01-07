<template>
  <div class="whiteBoxesContainer">
    <div class="individualBox">
      <img class="boxItem" src="../../assets/calendar-1.svg" alt="" />

      <p class="boxPara">Hastane Randevusu Alın</p>
    </div>
    <div class="individualBox">
      <img class="boxItem" src="../../assets/camera.svg" alt="" />
      <p class="boxPara">Görüntülü Görüşme Randevusu Alın</p>
    </div>
    <div class="individualBox">
      <img class="boxItem" src="../../assets/heart-circle.svg" alt="" />
      <p class="boxPara">Check-Up Başvurusu Yapın</p>
    </div>
    <div class="individualBox">
      <img class="boxItem" src="../../assets/bitcoin-convert.svg" alt="" />
      <p class="boxPara">Tıbbi İkinci Görüş Formu</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.whiteBoxesContainer {
  height: 12.5rem;
  border-bottom: 1px solid #dae9f1;
  width: 100%;
  /* border: 1px solid black; */
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  /* padding-bottom: 1.5em; */
  /* margin-top: 1.5em;

  margin-bottom: 1.5em; */
}
.individualBox {
  /* border: 1px solid black; */
  width: 100%;
  height: auto;
  background: #ffffff;
  box-shadow: 0px 3px 3px rgba(0, 0, 0, 0.03);
  border-radius: 10px;
  margin-right: 1em;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 1em;
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
  font-size: 18px;
  line-height: 20px;
  /* or 125% */
  font-weight: 900;
  text-align: left;
  color: #0a67ad;
}
</style>
