<template>
  <div id="LandingComponent">
    <div class="home">
      <b-container class="bv-example-row welcomeBox">
        <b-row>
          <!-- cols="5" sm="7" md="7" lg="7" xl="7"  -->
          <!-- banner -->
          <b-col cols="12" md="12" lg="7" class="banner">
            <div class="bannerTitleGeneral">
              <div class="bannerTitleDiv">
                <img src="../assets/logo.svg" alt="" />
              </div>

              <h3 class="onlineİslemler">ONLINE İŞLEMLER</h3>
            </div>

            <div class="bannerBody">
              <h2 class="bannerBodyTitle">
                Sevdiklerinizle sağlıklı ve uzun bir hayat
              </h2>
              <div class="bannerItemContainer">
                <img
                  class="bannerItemImage"
                  src="../assets/giris/calendar-1.svg"
                  alt=""
                />
                <h4 class="bannerItem">Randevu alın ve düzenleyin</h4>
              </div>

              <div class="bannerItemContainer">
                <img
                  class="bannerItemImage"
                  src="../assets/giris/health.svg"
                  alt=""
                />
                <h4 class="bannerItem">Test sonuçlarınızı görüntüleyin</h4>
              </div>

              <div class="bannerItemContainer">
                <img
                  class="bannerItemImage"
                  src="../assets/giris/calendar-1.svg"
                  alt=""
                />
                <h4 class="bannerItem">Geçmiş muayenelerinizi görün</h4>
              </div>
            </div>
          </b-col>
          <!-- sign up part -->
          <b-col cols="12" md="12" lg="5" class="signup">
            <div id="formPart">
              <h3 id="girisTitle">Giriş yapın</h3>
              <div class="inputGroup">
                <label id="inputField1Label" for="inputField1"
                  >Protokol No / TCKN</label
                ><br />
                <b-form-input
                  id="inputField1"
                  class="formInput"
                  type="text"
                ></b-form-input>
              </div>
              <div class="inputGroup">
                <label id="inputField1Label" for="inputField2">Parolanız</label
                ><br />
                <b-form-input
                  id="inputField2"
                  class="formInput"
                  type="password"
                ></b-form-input>
              </div>
              <button id="girisBtn">Tamam</button>
              <div id="paraDiv">
                <p id="girisPara">
                  <!-- <img src="../assets/flash-circle-1.png" alt="" /> -->

                  Şifremi unuttum
                </p>
              </div>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#LandingComponent {
  height: 100%;
  width: 100%;
}
.home {
  min-height: 60rem;
  max-height: 100%;
  width: 100%;
  background-color: #b9e1f5;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-left: 10%;
  padding-right: 10%;
}
.welcomeBox {
  border-radius: 20%;
  height: 100%;
  width: 100%;
}
.banner {
  height: auto;
  /* background-color: black; */
  background: url("../assets/giris/backgroundImg.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  border-top-left-radius: 5%;
  border-bottom-left-radius: 5%;
}
.bannerTitleGeneral {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.bannerTitleDiv {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  margin: 4em 0 0 3em;
  width: auto;
}
.onlineİslemler {
  margin: 4em 0 0 3em;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 20px;
  line-height: 18px;
  /* identical to box height, or 90% */
  text-align: center;
  color: #76d1ff;
}
.bannerBody {
  margin: 5em 0 0 3em;
  width: 60%;
  color: white;
}
.bannerItemContainer {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: flex-start;
  margin-top: 0.6em;
}
.bannerItemImage {
  margin-right: 0.5em;
}
.bannerItem {
  margin-bottom: 1em;
  padding-top: 0.4em;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: flex-start;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 20px;
  line-height: 18px;
  width: 100%;
  /* border: 1px solid black; */
}
/* form part */
#girisTitle {
  /* Giriş Yapın */
  width: 141px;
  height: 30px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: 800;
  font-size: 28px;
  line-height: 30px;
  /* identical to box height, or 107% */
  margin-bottom: 1.5em;
  color: #3c4e69;
}
.bannerBodyTitle {
  margin-bottom: 1.6em;
  margin-top: 3.5em;
  font-weight: 900;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 44px;
  /* or 122% */
  width: 80%;
  color: #ffffff;
}
.signup {
  height: auto;
  background-color: #b9e1f5;
  background-color: #f2f8fb;
  border-top-right-radius: 5%;
  border-bottom-right-radius: 5%;
}
#formPart {
  height: auto;
  width: 100%;
  display: flex;
  flex-direction: column;
  /* justify-content: flex-start;
  align-items: flex-start; */
  padding: 5em 6em 0 6em;
}
#inputField1Label {
  margin: 0;
  width: 122px;
  height: 20px;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 20px;
  /* identical to box height, or 143% */
  color: #818b9a;
}
.inputTitle {
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 20px;
}
.InputItem {
  background: #ffffff;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.15);
  border-radius: 6px;
}
.formInput {
  /* margin: 1em 0 1em 0;
  height: 5em !important; */
  width: 100%;
  height: 58px;
  background: #ffffff;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.15);
  border-radius: 6px;
  margin: 0 0 1em 0;
}
#girisBtn {
  color: #ffffff;
  border: none;
  width: 100%;
  height: 58px;
  background: #32a5df;
  border-radius: 6px;
  margin-top: 1em;
  margin-bottom: 7rem;
}
#paraDiv {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: flex-end;
  /* border: 1px solid black; */
  height: 100%;
  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 20px;
}
#girisPara {
  margin: 2em 0 2em 0;
}
</style>
