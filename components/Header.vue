<template>
  <header>
    <div>
      <h1><i><img src="~static/images/ic_book.png" alt="ブック"></i>ETC</h1>
      <address>
        <i><img src="~static/images/ic_tel.png" alt="電話"></i>
        <div>
          <a href="#">0120-123-123</a>
          <dl>
            <dt>受付時間｜</dt>
            <dd>
              <time>9:30</time>~<time>20:00</time>
            </dd>
            <dd>土日祝日を除く</dd>
          </dl>
        </div>
      </address>
      <a class="st-button" href="#sc-form">
        お問い合わせはこちら
      </a>
    </div>
  </header>
</template>
<style lang="scss" scoped>
header {
  background-color: #00d0d4;
  min-width: 1000px;
  > div {
    width: 965px;
    height: 73px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    > a {
      width: 210px;
      height: 45px;
    }
  }
}
i {
  display: grid;
}
h1 {
  display: inline-flex;
  align-items: center;
  font-size: 32px;
  margin-right: auto;
  color: #fff;
  i {
    margin-right: 14px;
  }
}
address {
  display: flex;
  align-items: center;
  margin-right: 20px;
  i {
    margin-right: 5px;
  }
  > div {
    display: flex;
    flex-direction: column;
  }
  a {
    font-size: 35px;
    color: #fff;
    line-height: 1;
    font-weight: bold;
  }
  dl {
    display: flex;
    align-items: center;
  }
  dt,
  dd,
  time {
    font-size: 12px;
    color: #fff;
    line-height: 1.5;
  }
  dd:last-child {
    margin-left: 10px;
  }
}
@media screen and (max-width: 780px) {
  header {
    width: 100%;
    min-width: auto;
    > div {
      width: 90%;
      margin: 0 auto;
      display: flex;
      align-items: center;
    }
  }
}
@media screen and (max-width: 680px) {
  header {
    > div {
      height: 16vw;
      > a {
        width: 40vw;
        height: 45px;
        box-sizing: border-box;
      }
    }
  }
  h1 {
    font-size: 5.3333vw;
    i {
      width: 5.5vw;
      margin-right: 1.66vw;
      img {
        width: 100%;
      }
    }
  }
  address {
    margin-right: 2.6666vw;
    a {
      font-size: 4.26666vw;
    }
    i {
      width: 12vw;
      margin-right: 0;
      img {
        width: 100%;
      }
    }
    > div {
      display: none;
    }
  }
}
</style>
