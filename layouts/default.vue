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
              <n-link to="/Second">
                PRODUCTIONAREA</n-link>
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
          <div class="Header__Acimage"><img v-bind:src="require(`@/assets/Images/svg/${img3}.webp`)" alt=""></div>
        </nav>
      </header>
      <Nuxt />
      <footer class="Footer">
        <section class="Footer__LinkConteiner">
          <div class="Footer__TextConteiner">
            <h2 class="Footer__HeadingText">
              Vin de Mondo. Access the Now.
            </h2>
            <div class="Footer__Productiintruduction">
              <nav class="Footer__Gnav">
                <p class="Footer__Productiin">Product Search</p>
                <ul id="example-1">
                  <li v-for="item in items" :key="item.message">
                    {{ item.message }}
                    {{ item.message }}
                    {{ item.message }}
                    {{ item.message }}
                    {{ item.message }}
                    {{ item.message }}
                    {{ item.message }}
                  </li>
                </ul>
              </nav>
              <nav class="Footer__Gnav">
                <p class="Footer__Productiin">Product Search</p>
                <ul class="Footer__ProductionConteiner">
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Red wine</n-link>
                  </li>
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Sparkling wine</n-link>
                  </li>
                  <li class="Footer__List">List of Production</li>
                  <li class="Footer__List">Areas</li>
                  <li class="Footer__List">List of producers</li>
                  <li class="Footer__List">Variety list</li>
                  <li class="Footer__List">Special feature list</li>
                  <li class="Footer__List">Wine set</li>
                  <li class="Footer__List">Wine goods</li>
                  <li class="Footer__List">wine cellar</li>
                </ul>
              </nav>
              <nav class="Footer__Gnav">
                <p class="Footer__Productiin">Product Search</p>
                <ul class="Footer__ProductionConteiner">
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Red wine</n-link>
                  </li>
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Sparkling wine</n-link>
                  </li>
                  <li class="Footer__List">List of Production</li>
                  <li class="Footer__List">Areas</li>
                  <li class="Footer__List">List of producers</li>
                  <li class="Footer__List">Variety list</li>
                  <li class="Footer__List">Special feature list</li>
                  <li class="Footer__List">Wine set</li>
                  <li class="Footer__List">Wine goods</li>
                  <li class="Footer__List">wine cellar</li>
                </ul>
              </nav>
              <nav class="Footer__Gnav">
                <p class="Footer__Productiin">Product Search</p>
                <ul class="Footer__ProductionConteiner">
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Red wine</n-link>
                  </li>
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Sparkling wine</n-link>
                  </li>
                  <li class="Footer__List">List of Production</li>
                  <li class="Footer__List">Areas</li>
                  <li class="Footer__List">List of producers</li>
                  <li class="Footer__List">Variety list</li>
                  <li class="Footer__List">Special feature list</li>
                  <li class="Footer__List">Wine set</li>
                  <li class="Footer__List">Wine goods</li>
                  <li class="Footer__List">wine cellar</li>
                </ul>
              </nav>
              <nav class="Footer__Gnav">
                <p class="Footer__Productiin">Product Search</p>
                <ul class="Footer__ProductionConteiner">
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Red wine</n-link>
                  </li>
                  <li class="Footer__List">
                    <n-link class="CC" to="#">Sparkling wine</n-link>
                  </li>
                  <li class="Footer__List">List of Production</li>
                  <li class="Footer__List">Areas</li>
                  <li class="Footer__List">List of producers</li>
                  <li class="Footer__List">Variety list</li>
                  <li class="Footer__List">Special feature list</li>
                  <li class="Footer__List">Wine set</li>
                  <li class="Footer__List">Wine goods</li>
                  <li class="Footer__List">wine cellar</li>
                </ul>
              </nav>
            </div>
          </div>
        </section>
      </footer>
    </main>
  </div>
</template>
<style lang="scss">
  .Main__Primary {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
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
