<template>
  <div>

  <b-container>
  <b-row>
    <b-col md="4"><div class="box"></div></b-col>
    <b-col md="4"><div class="box"></div></b-col>
        <b-col md="4"><div class="box"></div></b-col>
  </b-row>


</b-container>

</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang="scss" scoped >
.box{
  height: 50px;
  background: gray;
  width: 100%;
}
</style>