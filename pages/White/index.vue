<template>
  <div>
    <WineImage v-for="n of 30" :key="n"></WineImage>
    <button class="button">次へ</button>
  </div>
</template>
<style lang="scss" scoped>
.button{
      display: block;
      width: 200px;
      height: 50px;
      text-align: center;
      margin: 0 auto;
      border: solid 1px black;
      transition: all 0.3s ease;
      &:hover{
        transition: all 0.3s ease;
        background-color: rgb(53, 0, 32);
        box-shadow: 0px 0px 10px rgb(53, 0, 32);
        color: white;
      }
    }

</style>
<script>
  import WineImage from '@/components/WineImage.vue'
  export default {
    components: {
      WineImage
    }
  }

</script>
