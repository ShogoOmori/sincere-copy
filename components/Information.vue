<template>
  <section class="st-main">
    <h1 class="light title">
      無料でご依頼頂ける場合がございます。
    </h1>
    <h2 class="text-blue">
      <i>
        <img src="~static/images/ic_page.png" alt="弁護士費用">
      </i>
      <!-- <i class="st-bengoshi"/> -->
      弁護士費用特約でお得にご依頼頂けます
    </h2>
    <p class="st-bengoshi_desc">
      あなたの<em class="text-light">自動車保険に弁護士費用特約</em>が付いていれば、弁護士費用を<br>
      保険会社負担で弁護士に依頼することができます。<br>
      <span>※保険会社の条件によっては本人負担が生じる場合があります。</span>
    </p>
    <ul>
      <li>
        <dl>
          <dt class="blue">
            どんなタイミングで<br>契約できるの？
          </dt>
          <dd class="text-orange">
            <div>
              <em>自動車保険</em>の<br>オプション契約
            </div>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="blue">
            入っていなかったのだけれど、<br>何とかならない？
          </dt>
          <dd class="text-orange">
            <div>
              <em>ご家族</em>が、<br>契約されていれば、<br>適用可能
            </div>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="blue">
            限度額はあるの？
          </dt>
          <dd class="text-orange">
            <p>
              弁護士費用<br>＝300万円限度
            </p>
            <p>
              法律相談費用<br>=10万円限度
            </p>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="blue">
            相場はどれくらい？
          </dt>
          <dd class="text-orange">
            <p>
              弁護士費用<br>＝20万円＋獲得金額の10%
            </p>
            <p>
              法律相談費用<br>＝5,000～10,000円
            </p>
          </dd>
        </dl>
      </li>
    </ul>
  </section>
</template>
<style lang="scss" scoped>
h2 {
  text-align: center;
  font-size: 24px;
  i {
    margin-right: -5px;
  }
}
.st-bengoshi_desc {
  margin-top: 30px;
  text-align: center;
  line-height: 1.7;
  span {
    display: inline-block;
    margin-top: 10px;
    font-size: 0.8rem;
  }
}
ul {
  display: flex;
  justify-content: center;
  margin-top: 20px;
}
li {
  margin: 0 10px;
}
dl {
  border:solid 4px #0082d3;
  width: 230px;
  height: 230px;
  dt {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80px;
    text-align: center;
    font-weight: bold;
  }
  dd {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin: auto 0;
    height: calc(100% - 80px);
    text-align: center;
  }
  em {
    font-weight: bold;
    font-size: 1.5rem;
  }
}
</style>
