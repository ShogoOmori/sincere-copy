<template>
  <section>
    <h1 class="title light">
      経験豊富なチームがサポート！
    </h1>
    <div class="st-main">
      <h2 class="text-light">
        ご相談から解決まで<br>
        全て弁護士にお任せください！
      </h2>
      <p>
        弁護士法人ALGでは、交通事故に特化した弁護士と専属スタッフが<br>
        チームとなって、ご相談から解決までご依頼者様をサポートいたします。<br>
        交通事故に遭われ、大変な思いをされている方のお力になれるよう、<br>
        親切・丁寧な対応を心がけていますので、安心してお任せください。
      </p>
    </div>
    <ol>
      <li>
        <section>
          <div class="st-content">
            <h1 class="text-blue">
              1.お問い合わせ
            </h1>
            <p>
              <span class="text-light">お電話もしくはメールフォームより</span>お気軽にご相談下さい。<br>
              交通事故事件専属の受付スタッフが、事故状況や被害者の方のお悩み等を詳細にお伺いし、法律相談までに準備して頂きたい事項があればご案内いたします。<br>
              また、弁護士との<span class="text-light">法律相談は予約制</span>ですので、ご都合の良い日時をお伺いいたします。
            </p>
          </div>
          <img src="~static/images/ref_flow01.jpg" alt="スマホでお問い合わせ">
        </section>
      </li>
      <li>
        <section>
          <div class="st-content">
            <h1 class="text-blue">
              2.事前ミーティング
            </h1>
            <p>
              お電話でお伺いした内容を基に、<span class="text-light">弁護士と受付スタッフでミーティング</span>を行い、法律相談までに必要な準備事項を打ち合わせます。<br>
              また、弁護士は、ご相談までに可能なリサーチを行い、事件の方針、見通し等を検討します。
            </p>
          </div>
          <img src="~static/images/ref_flow02.jpg" alt="ミーティングのようす">
        </section>
      </li>
      <li>
        <section class="st-third_content">
          <div class="st-content_main">
            <div class="st-content">
              <h1 class="text-blue">
                3.法律相談（ご来所又は、お電話）
              </h1>
              <p>
                弁護士に疑問点やお悩みなどをお聞かせください。事前の聞き取りとリサーチに基づき、具体的なアドバイスをいたします。<br>
                また、<span class="text-light">見込まれる後遺障害等級、適正な損害賠償額、予想される争点など</span>事件の見通しを可能な限りご説明し、解決までの道筋と事案に応じ戦略をご提案いたします。もちろん、<span class="text-light">弁護士費用</span>についてもご説明いたします。
              </p>
            </div>
            <img src="~static/images/ref_flow03.jpg" alt="相談のようす">
          </div>
          <div class="st-item">
            <dl>
              <dt class="text-blue">
                来所相談の場合
              </dt>
              <dd>
                最寄りの本部または支部をご案内させて頂きます。<br>
                支部が無い地域にお住まいでも、電話による法律相談が可能です。
              </dd>
            </dl>
            <dl>
              <dt class="text-blue">
                お電話相談の場合
              </dt>
              <dd>
                予めスタッフがご都合の良い日時をお聞きし、時間になれば弁護士からお電話をさせて頂きます。
              </dd>
            </dl>
          </div>
        </section>
      </li>
      <li>
        <section>
          <div class="st-content">
            <h1 class="text-blue">
              4.ご契約
            </h1>
            <p>
              ご依頼頂ける場合、<span class="text-light">委任契約</span>を締結いたします。<br>
              内容についてご納得いただけてからの契約になりますので、後々に禍根を残すことなく、ご依頼いただけるかと思います。
            </p>
          </div>
          <img src="~static/images/ref_flow04.jpg" alt="握手">
        </section>
      </li>
      <li>
        <section>
          <div class="st-content">
            <h1 class="text-blue">
              5.ご契約
            </h1>
            <p>
              ご依頼頂ける場合、<span class="text-light">委任契約</span>を締結いたします。<br>
              内容についてご納得いただけてからの契約になりますので、後々に禍根を残すことなく、ご依頼いただけるかと思います。
            </p>
          </div>
          <img src="~static/images/ref_flow04.jpg" alt="握手">
        </section>
      </li>
    </ol>
  </section>
</template>
<style lang="scss" scoped>
.st-main {
  text-align: center;
}
li {
  width: 800px;
  margin: 70px auto;
  padding: 50px 80px;
  box-shadow: 5px 5px 5px rgba(0,0,0,0.2);
  position: relative;
  section {
    display: flex;
  }
  .st-content {
    width: 600px;
  }
  h1 {
    font-size: 26px;
  }
  p {
    font-size: 18px;
    margin-top: 20px;
  }
  img {
    margin-left: 50px;
  }
  &:not(:last-child) {
    &::after {
      content:'';
      position: absolute;
      right: 50%;
      bottom: -70px;
      width: 0;
      height: 0;
      border-left: 50px solid transparent;
      border-right: 50px solid transparent;
      border-top: 50px solid #ffb400;
    }
  }
}
.st-third_content {
  display: flex;
  flex-direction: column;
  .st-content_main {
    display: flex;
  }
  .st-item {
    display: flex;
    justify-content: space-between;
  }
}
dl {
  margin-top: 40px;
  width: 45%;
}
dt {
  font-weight: bold;
  font-size: 18px;
  &::before {
    content:'■';
    margin-right: 5px;
  }
}
dd {
  margin-top: 15px;
}
</style>
