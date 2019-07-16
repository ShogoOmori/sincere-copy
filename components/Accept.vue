<template>
  <section>
    <h1 class="title light">
      相談でこんなお悩みありませんか？
    </h1>
    <ul>
      <li class="light">
        <p>
          信頼できる<br>大きい事務所に<br>相談したい
        </p>
        <i>
          <img src="~static/images/ic_accept01.png" alt="大きい事務所">
        </i>
      </li>
      <li class="light">
        <p>
          遠方だと<br>相談に行くのが<br>大変
        </p>
        <i>
          <img src="~static/images/ic_accept02.png" alt="日本列島">
        </i>
      </li>
      <li class="light">
        <p>
          事務所まで<br>行く時間がない
        </p>
        <i>
          <img src="~static/images/ic_accept03.png" alt="砂時計">
        </i>
      </li>
      <li class="light">
        <p>
          交渉に強い<br>弁護士に<br>相談したい
        </p>
        <i>
          <img src="~static/images/ic_accept04.png" alt="弁護士">
        </i>
      </li>
      <li class="light">
        <p>
          示談金に<br>納得がいかない
        </p>
        <i>
          <img src="~static/images/ic_accept05.png" alt="納得がいかない人">
        </i>
      </li>
    </ul>
  </section>
</template>
<style lang="scss" scoped>
section {
  padding-bottom: 60px;
}
ul {
  display: flex;
  justify-content: center;
}
li {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 10px;
  padding: 10px;
  width: 160px;
  text-align: center;
  p {
    margin-bottom: 30px;
    font-size: 16px;
  }
}
@media screen and (max-width: 980px) {
 ul {
   flex-wrap: wrap;
 }
}
@media screen and (max-width: 680px) {
 li {
   width: 20vw;
   p {
    margin-bottom: 10px;
    font-size: 2.7vw;
  }
 }
 img {
   width: 12vw;
   object-fit: contain;
 }
}
</style>
