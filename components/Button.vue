<template>
  <section class="st-form">
    <div class="st-form_title light">
      <h1>
        損害賠償金額<span>無料診断</span>
      </h1>
      <p>
        保険会社提示の賠償金に<br class="sp-view">疑問を抱かれた方はご相談ください
      </p>
    </div>
    <div class="st-form_content">
      <a href="#" class="st-button">お問い合わせはこちら</a>
      <div class="st-form_access">
        <p>
          <span class="blue">24H</span>受付窓口にて、<br class="sp-view">無料診断ご希望の旨をお伝えください
        </p>
        <img src="~static/images/ic_tel_blue.png" alt="電話のマーク">
        <address>
          <a href="tel:0120-123-123" class="text-blue">0123-123-123</a>
          <p class="text-blue">
            受付時間 | 9:30~20:00 土日祝日を除く
          </p>
        </address>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.st-form {
  width: 900px;
  margin: 30px auto;
  border: solid 4px #00d0d3;
}
.st-form_title {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 70px;
  h1 {
    font-size: 30px;
    font-weight: normal;
    span {
      font-weight: bold;
    }
  }
}
.st-form_content {
  display: flex;
  padding: 5px;
  height: 200px;
  margin: 10px;
  span {
    display: inline-block;
    margin: 3px;
    padding: 3px;
    font-weight: bold;
  }
  p {
    font-weight: bold;
  }
  .st-form_access{
    margin-left: 20px;
  }
  address{
    a {
      font-size: 50px;
      font-weight: bold;
    }
  }
  .st-button {
    height: 100%;
    width: 50%;
  }
}
@media screen and (max-width: 980px) {
  .st-form_title {
    flex-direction: column;
  }
  .st-form {
    width: 90vw;
    margin: 30px auto;
  }
  .st-form_content {
    flex-direction: column;
    align-items: center;
    height: 50vh;
    .st-button {
      width: 80%;
      height: 100px;
      margin-bottom: 25px;
      font-size: 4vw;
    }
  }
}
@media screen and (max-width: 980px) {
  .st-form_title {
    height: 100px;
    p {
      text-align: center;
    }
  }
  .st-form_content {
    address{
      a {
        font-size: 45px;
      }
    }
  }
}
</style>
