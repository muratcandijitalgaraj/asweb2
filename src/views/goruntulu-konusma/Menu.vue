<template>
  <div class="menu">
    <!-- Giriş -->
    <div class="menuItem">
      <img src="../../assets/menu/route-square.svg" alt="" class="menuIcon" />
      <p class="menuPara">Giriş</p>
    </div>

    <!-- randevularım -->
    <div class="menuItem">
      <img src="../../assets/menu/calendar-1.svg" alt="" class="menuIcon" />
      <p class="menuPara">Randevularım</p>
    </div>

    <!-- test sonuçları -->
    <div class="menuItem">
    <div class="test-sonuclari">
  <img src="../../assets/menu/health.svg" alt="" class="menuIcon" />
      <p class="menuPara">Test Sonuçları</p>
    </div>
    <img src="../../assets/menu/1.svg" alt="">
    </div>
    <!-- geçmiş muayeneler -->
 <div class="menuItem">
      <img src="../../assets/menu/document-like.svg" alt="" class="menuIcon" />
      <p class="menuPara">Geçmiş Muayeneler</p>
    </div>

    <!-- hesabınız -->
  
 <div class="menuItem">
      <img src="../../assets/menu/personalcard.svg" alt="" class="menuIcon" />
      <p class="menuPara">Hesabınız</p>
    </div>
    <!-- şifre değiştir -->
 <div class="menuItem">
      <img src="../../assets/menu/setting-2.svg" alt="" class="menuIcon" />
      <p class="menuPara">Şifre Değiştir</p>
    </div>

    <!-- çıkış yap -->
 <div class="menuItem">
      <img src="../../assets/menu/import-2.svg" alt="" class="menuIcon" />
      <p class="menuPara">Çıkış Yap</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.menu {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: baseline;
  margin: 1.5em 0 0 1.5em;
}
.test-sonuclari {
  display: flex;
  flex-direction: row;
  /* justify-content: flex-start; */
  align-items: flex-start;
/* border: 1px solid black; */
margin-right: 0.7em;

}
.menuItem {
  /* margin-bottom: 1.3em; */
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: flex-start;
  height: 100%;
  width: auto;
  /* border: 1px solid black; */
  padding: 0;
  padding-right: 0.5em;
}
.notification {
  margin-left: 5px;
}
.menuIcon {
  margin-right: 0.6em;
}
.menuPara {
  /* border: 1px solid black; */
  width: auto;
/* width: 98px; */
height: 20px;
font-family: Nunito Sans;
font-style: normal;
font-weight: bold;
font-size: 16px;
line-height: 20px;
color: #475870;
}


</style>
