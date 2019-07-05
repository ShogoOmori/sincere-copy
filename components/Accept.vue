<template>
  <section class="st-accept">
    <h2 class="title light">
      相談でこんなお悩みありませんか？
    </h2>
    <ul>
      <li class="light">
        <p>信頼できる<br>大きい事務所に<br>相談したい</p>
        <i><img src="~static/images/ic_accept01.png" alt="相談"></i>
      </li>
      <li class="light">
        <p>遠方だと<br>相談に行くのが<br>大変</p>
        <i><img src="~static/images/ic_accept02.png" alt="遠方"></i>
      </li>
      <li class="light">
        <p>事務所まで<br>行く時間がない</p>
        <i><img src="~static/images/ic_accept03.png" alt="時間"></i>
      </li>
      <li class="light">
        <p>交渉に強い<br>弁護士に<br>相談したい</p>
        <i><img src="~static/images/ic_accept04.png" alt="強い"></i>
      </li>
      <li class="light">
        <p>示談金に<br>納得がいかない</p>
        <i><img src="~static/images/ic_accept05.png" alt="納得いかない"></i>
      </li>
    </ul>
  </section>
</template>
<style lang="scss" scoped>
.st-accept {
  margin-bottom: 80px;
}
ul {
  width: 960px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
}
li {
  width: 176px;
  height: 240px;
  padding: 30px 0;
  box-shadow: 2px 2px 2px rgba(0,0,0,0.16);
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
p {
  font-size: 16px;
  margin-bottom: auto;
}
@media screen and (max-width: 780px) {
  ul {
    width: 92.8%;
    margin: 0 auto;
    flex-wrap: wrap;
    justify-content: center;
  }
  li {
    margin-right: 2.6666vw;
    &:nth-child(2),
    &:last-child {
      margin-right: 0;
    }
    &:first-child,
    &:nth-child(2) {
      margin-bottom: 2.6666vw;
    }
    &:first-child{
      margin-left: 16vw;
    }
    &:nth-child(2) {
      margin-right: 16vw;
    }
  }
}
@media screen and (max-width: 680px) {
  .st-accept {
    margin-bottom: 21.3333vw;
  }
  li {
    width: 29vw;
    height: 38.67vw;
    padding: 3.7vw 0 4.8vw;
  }
  p {
    font-size: 3.2vw;
  }
  img {
    height: 12vw;
  }
}
</style>
