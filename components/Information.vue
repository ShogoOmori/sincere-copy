<template>
  <section class="st-inform">
    <h2 class="light title">
      無料でご依頼頂ける場合がございます。
    </h2>
    <section>
      <h3 class="text-blue">
        <i><img src="~static/images/ic_page.png" alt="アイコン"></i>弁護士費用特約で<br class="sp-view">
        お得にご依頼頂けます
      </h3>
      <p>
        あなたの<span class="text-light">自動車保険に弁護士費用特約</span>が付いていれば、弁護士費用を<br class="pc-view">
        保険会社負担で弁護士に依頼することができます。
      </p>
      <p class="remarks">
        ※保険会社の条件によっては本人負担が生じることがあります。
      </p>
    </section>
    <ul>
      <li>
        <dl>
          <dt class="blue">
            どんなタイミングで<br>契約できるの？
          </dt>
          <dd>
            <p class="text-orange">
              <strong>自動車保険</strong>の<br>オプション契約
            </p>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="blue">
            入っていなかったのだけれど、<br>何とかならない？
          </dt>
          <dd>
            <p class="text-orange">
              <strong>ご家族</strong>が、<br>
              契約されていれば、<br>
              適用可能
            </p>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="blue">
            限度額はあるの？
          </dt>
          <dd>
            <p class="text-orange">
              弁護士費用<br>＝<em>300</em>万円限度
            </p>
            <p class="text-orange">
              法律相談費用<br>=<em>10</em>万円限度
            </p>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="blue">
            相場はどれくらい？
          </dt>
          <dd>
            <p class="text-orange">
              弁護士費用<br>＝20万円＋獲得金額の10%
            </p>
            <p class="text-orange">
              法律相談費用<br>＝5,000～10,000円
            </p>
          </dd>
        </dl>
      </li>
    </ul>
  </section>
</template>
<style lang="scss" scoped>
.st-inform {
  margin-bottom: 120px;
  text-align: center;
  section {
    margin-bottom: 40px;
    p {
      font-size: 16px;
      line-height: 1.75;
    }
    p.remarks {
      margin-top: 10px;
      font-size: 14px;
    }
  }
  strong {
    font-size: 20px;
  }
  em {
    font-size: 18px;
  }
  p:nth-child(2) {
    margin-top: 20px;
  }
}
h3 {
  font-size: 28px;
  font-weight: normal;
  display: flex;
  align-items: flex-end;
  justify-content: center;
  font-weight: bold;
  letter-spacing: 0.05em;
  margin-bottom: 35px;
}
ul {
  display: flex;
  justify-content: space-between;
  width: 960px;
  margin: 0 auto;
}
li {
  width: 225px;
  height: 250px;
  box-sizing: border-box;
  border: 4px solid #0182d3;
  border-top: 0;
}
dl {
  height: 100%;
}
dt {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 90px;
  text-align: center;
  font-size: 14px;
  font-weight: bold;
}
dd {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction:column;
  height: calc(100% - 90px);
}
@media screen and (max-width: 780px) {
  ul {
    width: 65%;
    flex-wrap: wrap;
  }
  li {
    margin-bottom: 20px;
  }
}
@media screen and (max-width: 680px) {
  .st-inform {
    min-width: auto;
    p {
      width: 92.8%;
      margin: 0 auto;
    }
    p:nth-child(2) {
      margin-top: 0;
      font-size: 4.26666vw;
    }
    section {
      p.remarks {
        margin-top: 2.6666vw;
        font-size: 3.2vw;
      }
    }
  }
  h3 {
    font-size: 4.8vw;
    display: block;
    margin-bottom: 10.6666vw;
    img {
      width: 9.6vw;
    }
  }
  ul {
    flex-direction: column;
  }
  li {
    width: 66.7vw;
    height: 66.7vw;
    margin: 0 auto 5.3333vw;
    &:last-child {
      margin-bottom: 0;
    }
  }
  dt {
    height: 24vw;
    font-size: 4.26666vw;
  }
  dd {
    font-size: 4.26666vw;
    font-weight: bold;
    height: calc(100% - 24vw);
    strong {
      font-size: 5.3333vw;
    }
  }
}
</style>
