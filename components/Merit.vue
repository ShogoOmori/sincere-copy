<template>
  <section class="st-merit">
    <h2 class="light title">
      弁護士に相談するメリット
    </h2>
    <ul>
      <li>
        <section>
          <div>
            <h3 class="text-blue">
              請求金額が大幅に増える
            </h3>
            <p>
              損害賠償額は、自賠責保険＜任意保険＜裁判の順位算定額が高額となることが多いと言えます。<br>
              保険会社は任意保険の算定基準で示談金学を提示してきますが、弁護士は裁判の算定基準額で増額交渉を行います。
            </p>
          </div>
          <figure aria-label="グラフ">
            <img src="~static/images/ref_merit01.jpg" alt="自賠責保険基準 任意保険基準 裁判基準">
          </figure>
        </section>
      </li>
      <li>
        <section>
          <div>
            <h3 class="text-blue">
              保険会社とのやり取りは弁護士に
            </h3>
            <p>
              相手側もできるだけ賠償金額を少なくしたいと考えるのが当然です。<br>
              「保険会社からの提案に納得できない」「損害の一部を認めてくれない」など、交渉の経験が無い方は不安が多いことと思います。
            </p>
          </div>
          <figure>
            <img src="~static/images/ref_merit02.jpg" alt="やり取り">
          </figure>
        </section>
      </li>
      <li>
        <section>
          <div>
            <h3 class="text-blue">
              スピーディで柔軟な対応
            </h3>
            <p>
              一般的な法律事務所は、個人もしくは小規模体制で対応してます。<br>
              そのため、「連絡が取れない」「返事が遅い」「対応が遅い」といったお悩みが出やすい状態になっています。
            </p>
          </div>
          <figure>
            <img src="~static/images/ref_merit03.jpg" alt="対応">
          </figure>
        </section>
      </li>
    </ul>
  </section>
</template>
<style lang="scss" scoped>
.st-merit {
  background-color: #c8fafa;
  padding-bottom: 120px;
  section {
    display: flex;
    background-color: #fff;
    box-shadow: 2px 2px 2px rgba(0,0,0,0.16);
    div {
      padding: 30px 60px 30px 0;
    }
    p {
      padding-left: 30px;
      font-size: 16px;
      letter-spacing: 0.05em;
    }
  }
}
h3 {
  border-bottom: 2px solid #0082d3;
  padding:0 0 10px 30px;
  font-size: 22px;
  margin-bottom: 16px;
}
ul {
  width: 960px;
  margin: 0 auto;
}
li {
  margin-bottom: 40px;
}
li:last-child {
  margin-bottom: 0;
}
figure {
  display: grid;
  img {
    object-fit: cover;
    object-position: center;
  }
}
@media screen and (max-width: 780px) {
  .st-merit {
    section {
      flex-direction: column;
      padding-bottom: 40px;
    }
  }
  ul {
    width: 92.8%;
    margin: 0 auto;
  }
  figure {
    width: 94%;
    margin: 0 auto;
    img {
      width: 100%;
    }
  }
}
@media screen and (max-width: 680px) {
  .st-merit {
    section {
      padding-bottom: 15vw;
      div {
        width: 100%;
        padding: 16vw 6.6666vw 0 0;
        box-sizing: border-box;
      }
      p {
        padding-left: 6.6666vw;
        font-size: 4.26666vw;
        margin-bottom: 5.3333vw;
      }
    }
  }
  h3 {
    font-size: 4.8vw;
    padding: 0 0 2.6666vw 6.6666vw;
    margin-bottom: 2.6666vw;
  }
  li {
    margin-bottom: 5.5vw;
  }
}
</style>
