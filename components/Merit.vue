<template>
  <section class="st-main">
    <h1 class="title light">
      弁護士に相談するメリット
    </h1>
    <section>
      <div class="st-content">
        <h1 class="text-blue">
          請求金額が大幅に増える
        </h1>
        <p>
          損害賠償額は、自賠責保険＜任意保険＜裁判の順位算定額が高額となることが多いと言えます。<br>
          保険会社は任意保険の算定基準で示談金学を提示してきますが、弁護士は裁判の算定基準額で増額交渉を行います。
        </p>
      </div>
      <img src="~static/images/ref_merit01.jpg" alt="自賠責保険基準＜任意保険基準＜裁判基準">
    </section>
    <section>
      <div class="st-content">
        <h1 class="text-blue">
          保険会社とのやり取りは弁護士に
        </h1>
        <p>
          相手側もできるだけ賠償金額を少なくしたいと考えるのが当然です。<br>
          「保険会社からの提案に納得できない」「損害の一部を認めてくれない」など、交渉の経験が無い方は不安が多いことと思います。
        </p>
      </div>
      <img src="~static/images/ref_merit02.jpg" alt="弁護士とのやりとり">
    </section>
    <section>
      <div class="st-content">
        <h1 class="text-blue">
          スピーディで柔軟な対応
        </h1>
        <p>
          一般的な法律事務所は、個人もしくは小規模体制で対応してます。<br>
          そのため、「連絡が取れない」「返事が遅い」「対応が遅い」といったお悩みが出やすい状態になっています。
        </p>
      </div>
      <img src="~static/images/ref_merit03.jpg" alt="電話対応する男性">
    </section>
  </section>
</template>
<style lang="scss" scoped>
.st-main {
  background-color: #C8FAFA;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-bottom: 80px;
  >h1 {
    width: 100%;
  }
  section {
    background-color: #fff;
    display: flex;
    width: 900px;
    margin: 20px 0;
    box-shadow: 3px 3px 3px rgba(0,0,0,0.3);
    .st-content {
      width: 600px;
    }
    h1 {
      border-bottom: solid 2px #0082d3;
      font-size: 24px;
      padding: 30px 30px 10px;
    }
    p {
      padding: 20px 30px;
      font-size: 16px;
    }
  }
}
img {
  margin-bottom: 20px;
}
@media screen and (max-width: 980px) {
  .st-main {
    section {
      flex-direction: column;
      width: 90vw;
      .st-content {
        width: 100%;
      }
    }
    img {
      object-fit: contain;
    }
  }
}
@media screen and (max-width: 680px) {
  section {
    margin: 0;
    p {
      padding: 20px 30px;
      font-size: 10px;
    }
  }
}
</style>
