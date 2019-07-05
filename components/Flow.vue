<template>
  <section class="st-flow">
    <h2 class="title light">
      経験豊富なチームがサポート！
    </h2>
    <p><strong class="text-light">ご相談から解決まで<br>全て弁護士にお任せください！</strong></p>
    <p>
      弁護士法人ALGでは、交通事故に特化した弁護士と専属スタッフが<br class="pc-view">
      チームとなって、ご相談から解決までご依頼者様をサポートいたします。<br>
      交通事故に遭われ、大変な思いをされている方のお力になれるよう、<br class="pc-view">
      親切・丁寧な対応を心がけていますので、安心してお任せください。
    </p>
    <ol>
      <li>
        <section class="st-flow__list">
          <div>
            <h3 class="text-blue">
              1.お問い合わせ
            </h3>
            <p>
              <span class="text-light">お電話もしくはメールフォームより</span>お気軽にご相談下さい。<br>
              交通事故事件専属の受付スタッフが、事故状況や被害者の方のお悩み等を詳細にお伺いし、法律相談までに準備して頂きたい事項があればご案内いたします。<br>
              また、弁護士との<span class="text-light">法律相談は予約制</span>ですので、ご都合の良い日時をお伺いいたします。
            </p>
          </div>
          <figure aria-label="イメージ画像">
            <img src="~static/images/ref_flow01.jpg" alt="お問い合わせ">
          </figure>
        </section>
      </li>
      <li>
        <section class="st-flow__list">
          <div>
            <h3 class="text-blue">
              2.事前ミーティング
            </h3>
            <p>
              お電話でお伺いした内容を基に、<span class="text-light">弁護士と受付スタッフでミーティング</span>を行い、法律相談までに必要な準備事項を打ち合わせます。<br>
              また、弁護士は、ご相談までに可能なリサーチを行い、事件の方針、見通し等を検討します。
            </p>
          </div>
          <figure aria-label="イメージ画像">
            <img src="~static/images/ref_flow02.jpg" alt="ミーティング">
          </figure>
        </section>
      </li>
      <li>
        <section class="st-flow__list">
          <div>
            <h3 class="text-blue">
              3.法律相談（ご来所又は、お電話）
            </h3>
            <p>
              弁護士に疑問点やお悩みなどをお聞かせください。事前の聞き取りとリサーチに基づき、具体的なアドバイスをいたします。<br>
              また、<span class="text-light">見込まれる後遺障害等級、適正な損害賠償額、予想される争点など</span>事件の見通しを可能な限りご説明し、解決までの道筋と事案に応じ戦略をご提案いたします。もちろん、<span class="text-light">弁護士費用</span>についてもご説明いたします。
            </p>
          </div>
          <figure aria-label="イメージ画像">
            <img src="~static/images/ref_flow03.jpg" alt="相談">
          </figure>
          <div>
            <dl>
              <dt class="text-blue">
                ■ 来所相談の場合
              </dt>
              <dd>
                最寄りの本部または支部をご案内させて頂きます。<br>
                支部が無い地域にお住まいでも、電話による法律相談が可能です。
              </dd>
            </dl>
            <dl>
              <dt class="text-blue">
                ■ お電話相談の場合
              </dt>
              <dd>予めスタッフがご都合の良い日時をお聞きし、時間になれば弁護士からお電話をさせて頂きます。</dd>
            </dl>
          </div>
        </section>
      </li>
      <li>
        <section class="st-flow__list">
          <div>
            <h3 class="text-blue">
              4.ご契約
            </h3>
            <p>
              ご依頼頂ける場合、<span class="text-light">委任契約を締結</span>いたします。<br>
              内容についてご納得いただけてからの契約になりますので、後々に禍根を残すことなく、ご依頼いただけるかと思います。
            </p>
          </div>
          <figure aria-label="イメージ画像">
            <img src="~static/images/ref_flow04.jpg" alt="契約">
          </figure>
        </section>
      </li>
      <li>
        <section class="st-flow__list">
          <div>
            <h3 class="text-blue">
              5.事件対応
            </h3>
            <p>
              <span class="text-light">担当弁護士と事務スタッフ</span>が解決までサポートします。<br>
              相手方との交渉は、全て弁護士にお任せください。
            </p>
          </div>
          <figure aria-label="イメージ画像">
            <img src="~static/images/ref_flow05.jpg" alt="対応">
          </figure>
        </section>
      </li>
    </ol>
  </section>
</template>
<style lang="scss" scoped>
.st-flow {
  background-color: #f5f7f7;
  padding-bottom: 80px;
  > p {
    text-align: center;
    line-height: 1.75;
  }
  > p:nth-child(2) {
    margin-bottom: 35px;
  }
}
.st-flow__list {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  div:first-child {
    width: 570px;
  }
  div:last-child {
    width: 100%;
    margin-top: 30px;
    display: flex;
    justify-content:space-between;
  }
  p {
    font-size: 18px;
  }
}
h3 {
  font-size: 24px;
  margin-bottom: 30px;
}
strong {
  font-size: 30px;
}
ol {
  width: 960px;
  margin: 40px auto 0;
}
li {
  box-shadow: 2px 2px 2px rgba(0,0,0,0.16);
  margin-bottom: 80px;
  background-color: #fff;
  padding: 40px 80px;
  box-sizing: border-box;
  position: relative;
  -webkit-filter: drop-shadow(1px 2px 1px rgba(0,0,0,0.16));
}
li:last-child {
  margin-bottom: 0;
}
li::after {
  content: "";
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 43px 43px 0 43px;
  border-color: #ffb300 transparent transparent transparent;
  position: absolute;
  margin: 0 auto;
  display: block;
  left: 0;
  right: 0;
  bottom: -65px;
}
li:last-child::after {
  content: none;
}
dl {
  width: 380px;
  background-color: #f5f7f7;
  padding: 20px;
  box-sizing: border-box;
}
dt {
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 10px;
}
@media screen and (max-width: 780px) {
  .st-flow__list {
    flex-direction: column;
  }
  ol {
    width: 93.33333%;
  }
  figure {
    height: 300px;
    img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: center;
    }
  }
}
@media screen and (max-width: 680px){
  .st-flow {
    min-width: auto;
    > p {
      font-size: 4.26666vw;
      width: 93%;
      margin: 0 auto;
    }
  }
  .st-flow__list {
    p {
      font-size: 4.2666vw;
      margin-top: 2.6666vw;
    }
    div:first-child {
      width: 100%;
      order: 1;
    }
    div:last-child {
      margin-top: 5.3333vw;
      flex-direction: column;
      order: 2;
    }
  }
  h3 {
    font-size: 4.8vw;
    margin-bottom: 0;
    position: absolute;
    top: 5.3333vw;
  }
  strong {
    font-size: 4.8vw;
  }
  ol {
    margin: 10.6666vw auto 0;
  }
  li {
    padding: 13.4vw 6.67vw 5.3333vw;
    margin-bottom: 16vw;
    &::after {
      width: 0;
      height: 0;
      border-style: solid;
      border-width: 5.4vw 5.4vw 0 5.4vw;
      border-color: #ffb300 transparent transparent transparent;
      bottom: calc( -5.4vw - 5.3333vw);
    }
  }
  figure {
    height: 80vw;
  }
  dl {
    width: 100%;
    padding: 2.6666vw 3.2vw 5.3333vw;
    box-shadow: 1px 1.73px 2px hsla(0, 0%, 0%, 0.2);
    margin-bottom: 5.3333vw;
  }
  dt {
    font-size: 4vw;
    line-height: 1.5;
    margin-bottom: 2.6666vw;
  }
  dd {
    font-size: 4.26666vw;
    line-height: 1.31;
  }
}
</style>
