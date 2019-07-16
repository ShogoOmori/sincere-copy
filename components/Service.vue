<template>
  <section class="st-main">
    <h1 class="title light">
      医学の知識がなくては交渉に勝てません！
    </h1>
    <h2 class="text-blue">
      弁護士法人ETCでは、<br>
      医療事件に特化した事業部を設置！
    </h2>
    <p class="st-toptext">
      医療事故情報センター、複数の協力医師紹介団体の協力医師ネットワーク、<br>
      さらには、弁護士法人ALG独自の協力医師ネットワークで、<br>
      適切なサポートを可能にします！
    </p>
    <ol>
      <li>
        <section class="st-sub_section">
          <div class="st-title">
            <img src="~static/images/num_service01.png" alt="1">
            <h1 class="text-blue">
              高度な医学的知見
            </h1>
          </div>
          <img src="~static/images/ref_service01.jpg" alt="医師の協力">
          <p>
            事故の裁判は医学的な知見が必要になることも多くあります。<br>
            その際に<span class="text-light">医師の協力</span>を得られるか、協力を得られたとしても<span class="text-light">内容を理解できるか</span>は大きな違いとなります。
          </p>
        </section>
      </li>
      <li>
        <section class="st-sub_section">
          <div class="st-title">
            <img src="~static/images/num_service02.png" alt="2">
            <h1 class="text-blue">
              医学知識の習得
            </h1>
          </div>
          <img src="~static/images/ref_service02.jpg" alt="本棚">
          <p>
            私たちは法的知識はもちろん、<span class="text-light">医学的な知識</span>にも通じております。<br>
            そのため医師の言葉を確実に理解し、あなたに<span class="text-light">ふさわしい等級を得るため</span>のサポートを行えます。
          </p>
        </section>
      </li>
      <li>
        <section class="st-sub_section">
          <div class="st-title">
            <img src="~static/images/num_service03.png" alt="3">
            <h1 class="text-blue">
              協力医師との連携
            </h1>
          </div>
          <img src="~static/images/ref_service03.jpg" alt="頼れる医師">
          <p>
            私たちに協力してくれる医師の方々や、850冊を超える医学の専門書と更にそれ以上の法的知識と経験をもってあなたをバックアップいたします。
          </p>
        </section>
      </li>
    </ol>
  </section>
</template>
<style lang="scss" scoped>
.st-main {
  padding-bottom: 70px;
}
h2 {
  text-align: center;
  font-weight: bold;
  font-size: 30px;
  line-height: 1.8;
}
.st-toptext {
  margin-top: 30px;
  text-align: center;
}
ol {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
li {
  width: 300px;
  display: flex;
  margin: 0 20px;
}
.st-title {
  display: flex;
  flex-direction: row;
  align-items: flex-end;
  h1 {
    font-size: 22px;
    margin-left: 25px;
  }
}
.st-sub_section {
  margin-top: 30px;
  p {
    margin-top: 15px;
    font-weight: bold;
    font-size: 16px;
    line-height: 1.8;
  }
}
</style>
