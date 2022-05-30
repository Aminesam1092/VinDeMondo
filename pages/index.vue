<template>
  <div class="hooper-sample">
    <hooper class="hooper-sample__hooper" :settings="hooperSettings">
      <slide class="hooper-sample__slide">
        Hooperを<br>
        使って
      </slide>
      <slide class="hooper-sample__slide">
        簡単に<br>
        カルーセルを
      </slide>
      <slide class="hooper-sample__slide">
        実装してみる
      </slide>
      <slide class="hooper-sample__slide">
        最後のスライドは<br>ボタンだけを表示する
      </slide>
      <hooper-pagination slot="hooper-addons" />
      <hooper-navigation slot="hooper-addons" />
    </hooper>
  </div>
</template>
<style lang="scss" scoped>
 .hooper-sample {
    background-color: #d5d5d5;
    text-align: center;

    &__hooper {

    }

    &__slide {
      display: flex;
      justify-content: center;
      align-items: center;
    }

  }
  div {
    background-color: rgb(170, 170, 170);
    width: 1280px;
    height: 500px;
    margin: 10px auto;
  }

</style>

<script>
  export default {
    name: 'IndexPage',
    components: {
      Hooper,
      Slide,
      HooperPagination,
      HooperNavigation,
  }
  }

</script>
