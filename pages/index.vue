<template>
  <div class="page">
    <b-container>
      <b-row>
        <b-col cols="12" md="6" lg="4" xl="3"><div class="box"></div></b-col>
        <b-col cols="12" md="6" lg="4" xl="3"><div class="box"></div></b-col>
        <b-col cols="12" md="6" lg="4" xl="3"><div class="box"></div></b-col>
        <b-col cols="12" md="6" lg="4" xl="3"><div class="box"></div></b-col>
        <b-col cols="12" md="6" lg="4" xl="3"><div class="box"></div></b-col>
        <b-col cols="12" md="6" lg="4" xl="3"><div class="box"></div></b-col>
        <b-col cols="12" md="6" lg="4" xl="3"><div class="box"></div></b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style lang="scss" scoped>
.page {
  margin: 100px 0;

  .box {
    height: 50px;
    background: gray;
    width: 100%;
    margin-bottom: 40px;
  }
}
</style>
