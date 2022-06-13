<template>
  <div>
    <footer class="Footer">
      <section class="Footer__LinkConteiner">
        <div class="Footer__TextConteiner">
          <h2 class="Footer__HeadingText">
            Vin de Mondo. Access the Now.
          </h2>
          <div class="Footer__Productiintruduction">
            <nav class="Footer__Gnav">
              <p class="Footer__Productiin">Product Search</p>
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
  </div>
</template>
<style lang="scss" scoped>
.Footer {
    margin-top: auto;
    width: 100%;
    margin-top: 20px;
    padding: 5px;
    background-color: rgb(53, 0, 32);
    font-family: 'PT_Serif';
    color: white;
    &__LinkConteiner {
      margin: 20px;
    }
    &__Productiintruduction{
      display: flex;
      justify-content: start;
      align-items: center;
      gap: 50px;
    }
    &__TextConteiner{
      max-width: 100%;
      margin: 0 auto;
    }
    &__Productiin{
      font-size: clamp(14px, calc(0.7407407407vw + 21.3333333333px), 28px);
    }
    &__HeadingText {
      font-size: clamp(24px, calc(0.7407407407vw + 21.3333333333px), 32px);
    }
    &__List{
      font-size: clamp(14px, calc(0.7407407407vw + 21.3333333333px), 16px);
    }
  }

</style>
<script>
  export default {
    name: 'FooterMenu',
  }

</script>
