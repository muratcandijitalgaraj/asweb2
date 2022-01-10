<template>
  <div id="girisComponent">
    <b-container>
      <b-row class="container">
        <b-col cols="12" md="12" lg="7">
          <div class="groupWithPicture">
            <div class="upperPart">
              <div class="logo">
                <img src="../assets/giris/logo.svg" alt="" />
              </div>
              <div class="online-islemler">ONLINE İŞLEMLER</div>
            </div>
            <div class="lowerPart">
              <div class="lowerTitle">
                Sevdiklerinizle sağlıklı ve uzun bir hayat
              </div>
              <div class="lowerGroup">
                <div class="groupItem">Randevu alın ve düzenleyin</div>
              </div>
            </div>
          </div>
        </b-col>
        <b-col cols="12" md="12" lg="5"> <div class="formGroup"></div> </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#girisComponent {
  background: #b9e1f5;
  height: 100vh;
  width: 100%;
  padding: 8rem;
}
/* .container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
} */
.groupWithPicture {
  background: url("../assets/giris/backgroundImg.svg");
  height: 50em;
  width: 100%;
  /* border-top-left-radius: 5%;
  border-bottom-left-radius: 5%; */
  background-repeat: no-repeat;
  background-size: 100%;
}
.formGroup {
  background: #f2f8fb;
  height: 50em;
  width: 100%;
}
.upperPart {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  padding: 3em 3em 0 3em;
}
.logo {
  margin-right: 2em;
}
.online-islemler {
  width: auto;
  height: 18px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 18.5px;
  line-height: 18px;
  /* identical to box height, or 90% */
  text-align: center;
  margin-top: 0.8em;
  color: #76d1ff;
}
</style>
