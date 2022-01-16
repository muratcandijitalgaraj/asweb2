<template>
  <div class="menuComponent">
    <div class="userGroup">
      <div class="userImg"><img src="../../assets/userGroup.svg" alt="" /></div>
      <div class="userText">
        <div class="userTitle">Mehmet Yılmazer</div>
        <div class="protokol-no">Protokol No: 292390</div>
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
  margin-left: 1.875rem;
}
.userGroup {
  margin-top: 2.438rem;
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
</style>
