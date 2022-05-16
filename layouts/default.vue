<template>
  <div>
    <main class="Main__Primary">
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
          <div class="Header__Acimage"><img v-bind:src="require(`@/assets/Images/svg/${img3}.webp`)" alt=""></div>
        </nav>
      </header>
      <Nuxt />
      <footer class="Footer">
        <div class="Footer__LinkConteiner">
          <h2 class="Footer__HeadingText">
            Vin De Mondo
          </h2>
        </div>
      </footer>
    </main>
  </div>
</template>

<style lang="scss">
  .Main__Primary {
    display: flex;
    flex-direction: column;
    min-height: 100vh;

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

      &__Acimage {
        width: 30px;
        height: 30px;
        border-radius: 50%;
        cursor: pointer;
        -webkit-transition: all 0.3s ease;
        -moz-transition: all 0.3s ease;
        -o-transition: all 0.3s ease;
        transition: all 0.3s ease;

        &:hover {
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

    .Footer {
      margin-top: auto;
      width: 100%;
      background-color: rgb(53, 0, 32);
      font-family: 'PT_Serif';
      color: white;

      &__LinkConteiner {
        margin: 20px;
      }

      &__HeadingText {
        font-size: clamp(24px, calc(0.7407407407vw + 21.3333333333px), 32px);
      }
    }
  }

</style>

<script>
  export default {
    data() {
      return {
        img1: 'Logo',
        img2: 'Logo2',
        img3: 'account'
      }
    }
  }

</script>
