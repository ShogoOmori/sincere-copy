<template>
  <section class="st-perform">
    <h2 class="light title">
      厚いご信頼を支える膨大な実績
    </h2>
    <p><strong class="text-blue">弁護士法人ETCは解決実績8000件以上!!</strong></p>
    <ul>
      <li><img src="~static/images/ref_perform01.jpg" alt="お客様1"></li>
      <li><img src="~static/images/ref_perform02.jpg" alt="お客様2"></li>
      <li><img src="~static/images/ref_perform03.jpg" alt="お客様3"></li>
      <li><img src="~static/images/ref_perform04.jpg" alt="お客様4"></li>
    </ul>
    <p>
      <span class="text-light">むちうちの人も治療中の人</span>も、<span class="text-light">後遺障害認定が難しいと言われた人</span>も、<br>
      どんなことでもご相談ください。<br>
      <span class="text-light">ETC独自のリーガルスタッフシステム</span>で、弁護士とスタッフがタッグを組んで、<br>
      事故状況を徹底的に聞き取り、洗い直して調査することで、有利な証拠を発見します。
    </p>
  </section>
</template>
<style lang="scss" scoped>
.st-perform {
  margin-bottom: 80px;
}
p {
  text-align: center;
  line-height: 1.75;
}
strong {
  font-size: 30px;
}
img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
}
ul {
  display: flex;
  margin: 40px 0 30px;
}
@media screen and (max-width: 680px) {
  strong {
    font-size: 4.8vw;
  }
  ul {
    margin: 10.6vw auto;
  }
  p {
    font-size: 4.26666vw;
    width: 92.8%;
    margin: 0 auto;
  }
}
</style>
