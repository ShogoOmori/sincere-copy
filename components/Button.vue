<template>
  <section class="st-return">
    <div>
      <h2>損害賠償金額<em>無料診断</em></h2>
      <p>保険会社提示の賠償金に<br class="sp-view">疑問を抱かれた方はご相談ください</p>
    </div>
    <div>
      <a class="st-button" href="#sc-form">
        お問い合わせはこちら
      </a>
      <address>
        <p><span class="blue">24H</span>受付窓口にて、<br class="sp-view">無料診断ご希望の旨をお伝えください</p>
        <i><img src="~static/images/ic_tel_blue.png" alt="電話"></i>
        <div>
          <a href="#">0120-123-123</a>
          <dl>
            <dt>受付時間｜</dt>
            <dd>
              <time datetime="09:30">9:30</time>~<time>20:00</time>
            </dd>
            <dd>土日祝日を除く</dd>
          </dl>
        </div>
      </address>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.st-return {
  width: 960px;
  margin: 40px auto;
  border: 4px solid #69e1e0;
  border-top: 0;
  box-sizing: border-box;
  > div:first-child {
    background-color: #69e1e0;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 74px;
  }
  > div:last-child {
    display: flex;
    justify-content: space-between;
    padding: 16px 35px;
    > a {
      width: 442px;
      font-size: 20px;
      font-weight: bold;
    }
  }
}
h2 {
  font-size: 30px;
  font-weight: normal;
  em {
    font-weight: bold;
  }
}
dl {
    display: flex;
    align-items: center;
  }
  dt,
  dd,
  time {
    font-size: 16px;
    color: #0082d3;
    line-height: 1.5;
    font-weight: bold;
    letter-spacing: 0.05em;
  }
  dd:last-child {
    margin-left: 10px;
  }
  address {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  margin-right: 20px;
  width: 400px;
  > p {
    width: 100%;
    font-weight: bold;
    margin-bottom: 7px;
    span {
      display: inline-flex;
      margin-right: 7px;
      width: 40px;
      height: 25px;
      justify-content: center;
      align-items: center;
    }
  }
  i {
    margin-right: 10px;
  }
  > div {
    display: flex;
    flex-direction: column;
  }
  a {
    font-size: 50px;
    color: #0082d3;
    line-height: 1;
    font-weight: bold;
  }
}
@media screen and (max-width: 780px) {
  .st-return {
    width: 92.8%;
    > div:first-child {
      flex-direction: column;
    }
    > div:last-child {
      flex-direction: column;
      align-items: center;
      > a {
        height: 75px;
      }
    }
  }
  address {
    margin: 60px 0 0;
  }
}
@media screen and (max-width:680px) {
  .st-return {
    width: 92.8vw;
    margin: 10.6666vw auto;
    > div:first-child {
      height: 26.6666vw;
      p {
        font-size: 3.2vw;
        text-align: center;
      }
    }
    > div:last-child {
      flex-direction: column;
      padding: 5.73333vw;
      > a {
        width: 100%;
        font-size: 4.8vw;
        height: 20vw;
      }
    }
  }
  h2 {
    font-size: 4.8vw;
    margin-bottom: 2.6666vw;
  }
  address {
    width: 100%;
    margin: 12vw 0 0;
    > p {
      display: flex;
      align-items: center;
      margin-bottom: 2.6vw;
      span {
        width: 10.6666vw;
        height: 6.6666vw;
        margin-right: 2.4vw;
      }
    }
    a {
      font-size: 9.3333vw;
    }
    img {
      width: 16vw;
    }
  }
  dt,
  dd,
  time {
    font-size: 3.2vw;
  }
}
</style>
