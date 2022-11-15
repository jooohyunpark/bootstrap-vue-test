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

    <b-container>
      <b-row
        ><b-col>
          <b-carousel
            id="carousel-1"
            controls
            indicators
            :interval="0"
            background="#ababab"
            img-width="1024"
            img-height="480"
            style="text-shadow: 1px 1px 2px #333"
          >
            <b-carousel-slide
              img-src="https://picsum.photos/1024/480/?image=1"
            ></b-carousel-slide>
            <b-carousel-slide
              img-src="https://picsum.photos/1024/480/?image=2"
            ></b-carousel-slide>
            <b-carousel-slide
              img-src="https://picsum.photos/1024/480/?image=3"
            ></b-carousel-slide>
          </b-carousel> </b-col
      ></b-row>
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
    background: #181818;
    width: 100%;
    margin-bottom: 40px;
  }
}
</style>
