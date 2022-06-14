<template>
  <div class="d">
    <section class="Cart">
      <section class="Cart__Info">
        <h2 class="Cart__Headingtext">カート</h2>
        <p class="Cart__Text">カートに入った状態では在庫が確保できておりません。注文完了をもって在庫確保となりますので、ご注意ください。</p>
        <div class="Cart__WineBox">
          <div class="Cart__WineConteiner">
            <img class="Cart__Image" src="@/assets/Images/webp/r1.webp">
            <div class="Cart__Conteiner">
            <h2 class="Wine__Name">シャトーセネジャック</h2>
            <p class="Cart__Explention">赤ワイン 2021年 750ml</p>
            <p class="Cart__Explention">モンテス</p>
            </div>
          </div>
          <div class="Cart__WineSecondConteiner">
              <p class="Cart__SText">商品合計 1,650円(税込)</p>
              <p class="Cart__SText">送料 0円(税込)</p>
              <p class="Cart__SText">クール代 330円(税込)</p>
              <p class="Cart__SecondText">合計 3,675</p>
              <button class="Cart__FB">ご購入手続きに進む</button>
          </div>
        </div>
      </section>
    </section>
  </div>
</template>
<style lang="scss" scoped>
  .Cart {
    width: 100%;
    margin-top: 100px;

    &__Info {
      padding: 0 50px;
    }

    &__Headingtext {
      font-size: 18px;
    }
    &__Explention{
        color: rgb(125, 125, 125);
        color: 16px;
    }
    &__Conteiner{
        padding: 30px;
    }
    &__Text {
      font-size: 12px;
      margin: 20px 0;
    }

    &__WineBox {
    width: 50%;
      margin: 50px auto;
      display: flex;
      align-items: center;
    }

    &__WineConteiner {
      padding: 60px;
      display: flex;
      align-items: center;
      justify-content: start;
      gap: 40px;
    border-top: 0.5px solid rgb(113, 0, 79);
       border-bottom: 0.5px solid rgb(113, 0, 79);
    }
    &__WineSecondConteiner{
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 40%;
        border: 0.5px solid rgb(113, 0, 79);
    }
    &__SecondText{
        width: 100%;
        text-align: right;
        font-weight: 900;
        padding:0 10px;
        font-size: 14px;
    }
        &__SText{
        width: 100%;
        padding: 0px 10px;
        text-align: right;
        font-weight: 900;
        font-size: 14px;
        margin: 10px;
        color: rgb(168, 168, 168);
    }
    &__FB{
        border-radius: 10px;
        margin: 10px;
        width: 70%;
        height: 30px;
        border: 0.5px solid rgb(113, 0, 79);
         transition: all 0.3s ease;
          &:hover{
        border-radius: 10px;
        margin: 10px;
        width: 70%;
        height: 30px;
        color: white;
        background-color: rgb(113, 0, 79);
         transition: all 0.3s ease;
    }
    }
    &__Image {
      width: 10%;
      height: 10%;
    }
  }

</style>
