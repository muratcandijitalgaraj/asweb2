<template>
  <div class="menuComponent">
    <div class="userGroup">
      <div class="userImg"><img src="../../assets/userGroup.svg" alt="" /></div>
      <div class="userText">
        <div class="userTitle">Mehmet Yılmazer</div>
        <div class="protokol-no">Protokol No: 292390</div>
      </div>
    </div>
    <div class="lineContainer">
      <div class="greyLine"></div>
    </div>
    <div class="itemContainer">
      <div class="menuItem">
        <div class="itemLogo">
          <img src="../../assets/menu/route-square.svg" alt="" />
        </div>
        <div class="itemPara">Giriş</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.menuComponent {
  width: 230px;
  border: 1px solid black;
  height: 100%;
  /* margin-left: 1.875rem; */
  margin-right: 1.875rem;
}
.lineContainer {
  display: flex;
  justify-content: center;
  align-items: center;
}
.greyLine {
  height: 1px;
  width: 100%;
  background: #dae9f1;
}
.userGroup {
  margin-top: 15%;
  margin-bottom: 10%;
  /* border: 1px solid black; */
}
.userImg {
  margin-bottom: 1.5rem;
}
.userTitle {
  height: 20px;

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  line-height: 20px;
  margin-bottom: 3px;

  color: #3c4e69;
}
.protokol-no {
  height: 18px;

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 18px;
  /* identical to box height */

  color: #3c4e69;
}
.itemContainer {
  /* border: 1px solid red; */
  padding-left: 1.875rem;
}
.menuItem {
  display: flex;
  flex-direction: row;
  /* justify-content: center; */
  align-items: center;
  /* border: 1px solid red; */
}
.itemLogo {
  width: auto;
  height: auto;
  margin-right: 0.5rem;
}
.itemPara {
  margin-top: 0.2rem;
  width: 32px;
  height: 20px;

  font-family: Nunito Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  line-height: 20px;

  color: #32a5df;
}
</style>
