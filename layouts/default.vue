<template>
  <div>
    <header class="Header">
      <nav class="Header__Nav">
        <div class="Header__Logo"><img v-bind:src="require(`@/assets/Images/svg/${img1}.svg`)" alt=""></div>
        <ul class="Header__Ul">
          <li class="Header__List">
            <n-link to="/">VARIETAL</n-link>
          </li>
          <li class="Header__List">
            <n-link to="/Second">
              REGION</n-link>
          </li>
          <li class="Header__List">
            <n-link to="">
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
        <img src="assets/Images/svg/account.svg" alt="">
      </nav>
    </header>
    <Nuxt />
    <footer class="Footer">
      <h2 class="Footer__HeadingText">
        Vin De Mondo
      </h2>
      <div class="Footer__LinkConteiner">
        
      </div>
    </footer>
  </div>
</template>

<style lang="scss">
  .Header {
    width: 100%;
    padding: 10px;
    font-size: 14px;
    font-family: 'PT_Serif';
    border-bottom: solid 0.5px rgb(187, 187, 187);
    background-color: white;

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
      -webkit-transition: all 0.3s ease;
      -moz-transition: all 0.3s ease;
      -o-transition: all 0.3s ease;
      transition: all 0.3s ease;

      &:hover {
        background-color: rgb(113, 0, 79);
        box-shadow: 0px 0px 5px rgb(113, 0, 79);
        -webkit-transition: all 0.3s ease;
        -moz-transition: all 0.3s ease;
        -o-transition: all 0.3s ease;
        transition: all 0.3s ease;
      }
    }

    &__Painting {
      width: 100px;
      height: 25px;
      -webkit-transition: all 0.3s ease;
      -moz-transition: all 0.3s ease;
      -o-transition: all 0.3s ease;
      transition: all 0.3s ease;

      &:hover {
        color: white;
        -webkit-transition: all 0.3s ease;
        -moz-transition: all 0.3s ease;
        -o-transition: all 0.3s ease;
        transition: all 0.3s ease;
      }
    }
  }

</style>

<script>
  export default {
    data() {
      return {
        img1: 'Logo',
        img2: 'Logo2'
      }
    }
  }

</script>
