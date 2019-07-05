<template>
  <section class="st-service">
    <h2 class="light title">
      医学の知識がなくては交渉に勝てません！
    </h2>
    <p><strong class="text-blue">弁護士法人ETCでは、<br>医療事件に特化した事業部を設置！</strong></p>
    <p>
      医療事故情報センター、複数の協力医師紹介団体の協力医師ネットワーク、<br>
      さらには、弁護士法人ALG独自の協力医師ネットワークで、<br>
      適切なサポートを可能にします！
    </p>
    <ol>
      <li>
        <section>
          <h3 class="text-blue">
            <img src="~static/images/num_service01.png" alt="1">高度な医学的知見
          </h3>
          <figure>
            <img src="~static/images/ref_service01.jpg" alt="知見">
          </figure>
          <p>
            事故の裁判は医学的な知見が必要になることも多くあります。<br>
            その際に<span class="text-light">医師の協力</span>を得られるか、協力を得られたとしても<span class="text-light">内容を理解できるか</span>は大きな違いとなります。
          </p>
        </section>
      </li>
      <li>
        <section>
          <h3 class="text-blue">
            <img src="~static/images/num_service02.png" alt="2">医学知識の習得
          </h3>
          <figure>
            <img src="~static/images/ref_service02.jpg" alt="習得">
          </figure>
          <p>
            私たちは法的知識はもちろん、<span class="text-light">医学的な知識</span>にも通じております。<br>
            そのため医師の言葉を確実に理解し、あなたに<span class="text-light">ふさわしい等級を得るため</span>のサポートを行えます。
          </p>
        </section>
      </li>
      <li>
        <section>
          <h3 class="text-blue">
            <img src="~static/images/num_service03.png" alt="3">協力医師との連携
          </h3>
          <figure>
            <img src="~static/images/ref_service03.jpg" alt="連携">
          </figure>
          <p>
            私たちに<span class="text-light">協力してくれる医師の方々</span>や、850冊を超える<span class="text-light">医学の専門書</span>と更にそれ以上の<span class="text-light">法的知識と経験</span>をもってあなたをバックアップいたします。
          </p>
        </section>
      </li>
    </ol>
  </section>
</template>
<style lang="scss" scoped>
.st-service {
  margin-bottom: 60px;
  > p {
     text-align: center;
     line-height: 1.75;
  }
  p:nth-child(2) {
    margin-bottom: 30px;
  }
}
h3 {
  text-align: center;
  position: relative;
  margin-bottom: 16px;
  font-size: 22px;
  line-height: 1;
  img {
    position: absolute;
    left: 0;
    bottom: 0;
  }
}
ol {
  display: flex;
  justify-content: space-between;
  width: 960px;
  margin: 60px auto 0;
}
li {
  width: 300px;
  p {
    margin-top: 18px;
    font-size: 16px;
    font-weight: bold;
    line-height: 1.75;
    letter-spacing: 0.05em;
  }
}
strong {
  font-size: 30px;
}
figure {
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
  }
}
@media screen and (max-width: 780px) {
  ol {
    width: 100%;
    flex-direction: column;
    align-items: center;
  }
  li {
    width: 80vw;
    margin-bottom: 60px;
    &:last-child {
      margin-bottom: 0;
    }
    p {
      font-size: 16px;
      margin-top: 20px;
    }
  }
}
@media screen and (max-width: 680px) {
  .st-service {
    margin-bottom: 21.3333vw;
    > p {
      width: 94%;
      margin: 0 auto 10.6vw;
    }
    > p:nth-child(3) {
      font-size: 4.26666vw;
    }
  }
  h3 {
    font-size: 4.8vw;
    margin-bottom: 3.2vw;
    img {
      height: 8vw;
      left: 13vw;
      bottom: -1vw;
    }
  }
  strong {
    font-size: 4.8vw;
  }
  li {
    width: 80vw;
    margin-bottom: 13.3333vw;
    p {
      font-size: 4.26666vw;
      margin-top: 5vw;
    }
  }
}
</style>
