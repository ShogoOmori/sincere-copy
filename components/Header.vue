<template>
  <header class="light">
    <div class="header-left">
      <i>
        <img src="~static/images/ic_book.png" alt="株式会社ETC">
      </i>
      <a href="#">ETC</a>
    </div>
    <div class="header-right">
      <i>
        <img src="~static/images/ic_tel.png" alt="電話番号はこちら">
      </i>
      <div class="st-contact">
        <address>
          <a href="tel:0120-123-123">0123-123-123</a>
          <p>
            受付時間 | 9:30~20:00 土日祝日を除く
          </p>
        </address>
      </div>
      <a href="#" class="st-button">お問い合わせはこちら</a>
    </div>
  </header>
</template>
<style lang="scss" scoped>
header {
  display: flex;
  justify-content:center;
  align-items: center;
  height: 80px;
}
.header-left {
  margin-right: 350px;
    display: flex;
    align-items: center;
    justify-content: center;
  i {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 50px;
    height: 50px;
  }
  a {
    line-height: 40px;
    color: #fff;
    font-size: 40px;
    font-weight: bold;
  }
}
.header-right {
  display: flex;
  align-items:center;
  i {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 50px;
    height: 50px;
    img {
      margin-right: 10px;
    }
  }
}
.st-contact {
  a {
    font-size: 35px;
    font-weight: bold;
    color: #fff;
  }
  p {
    font-size: 12px;
  }
}
.st-button {
  height: 50px;
  padding: 0 30px;
  margin-left: 10px;
}
</style>
