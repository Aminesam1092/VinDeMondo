<template>
    <div>
              <header class="Header">
        <nav class="Header__Nav">
          <div class="Header__Logo"><img v-bind:src="require(`@/assets/Images/svg/${img1}.svg`)" alt=""></div>
          <ul class="Header__Ul">
            <li class="Header__List">
              <n-link to="/">PRODUCTIONAREA</n-link>
            </li>
            <li class="Header__List">
              <n-link to="/Red">
                RED WINE</n-link>
            </li>
            <li class="Header__List">
              <n-link to="/White">
                WHITE WINE</n-link>
            </li>
            <li class="Header__List">
              <n-link to="#">
                GIFT</n-link>
            </li>
            <li class="Header__List">
              <n-link to="/Second">
                NEWS</n-link>
            </li>
          </ul>
          <ul class="Header__Account">
            <li class="Header__AcList">
              <n-link class="Header__Painting" to="">
                Sign Up</n-link>
            </li>
            <li class="Header__AcList">
              <n-link class="Header__Painting" to="">
                Sign In</n-link>
            </li>
          </ul>
           <div class="Header__Acimage"><n-link to="/Cart"><img v-bind:src="require(`@/assets/Images/svg/${img4}.svg`)" alt=""></n-link></div>
          <div class="Header__Acimage"><img v-bind:src="require(`@/assets/Images/svg/${img3}.webp`)" alt=""></div>
        </nav>
      </header>
    </div>
</template>
<style lang="scss" scoped>

  .Header {
    width: 100%;
    padding: 10px;
    font-size: 14px;
    font-family: 'PT_Serif';
    border-bottom: solid 0.5px rgb(187, 187, 187);
    background-color: white;
    position: fixed;
     box-shadow: 0px 0px 10px rgb(91, 91, 91);
    &__Nav {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 15px;
    }
    &__Logo {
      width: 15%;
      margin-right: auto;
    }
    &__Ul {
      display: flex;
      justify-content: center;
      align-content: center;
      gap: 15px;
    }
    &__Account {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 10px;
    }
    &__AcList {
      width: 100px;
      height: 25px;
      border: solid 1px rgb(113, 0, 79);
      text-align: center;
      line-height: 20px;
      &:hover {
        background-color: rgb(113, 0, 79);
        box-shadow: 0px 0px 5px rgb(113, 0, 79);
      }
    }
    &__Acimage {
      width: 30px;
      height: 30px;
      cursor: pointer;
    }
    &__Painting {
      width: 100px;
      height: 25px;
      &:hover {
        color: white;
      }
    }
  }
</style>
<script>
  export default{
    name: 'HeaderMenu',
        data() {
      return {
        img1: 'Logo',
        img2: 'Logo2',
        img3: 'account',
        img4:  'ca-to',
      }
    }
  }
</script>