<template>
  <section class="st-main">
    <div>
      <h2 class="text-light">
        <span>
          <em><span class="text-blue">保険会社</span>から<br>提示された</em>
          <span><span class="text-blue">賠償金額</span>を</span>
        </span>
        <strong class="text-blue">無料診断</strong>
      </h2>
      <p class="text-light">
        増額しなければ、成功報酬はいただきません
      </p>
      <div class="st-main__detail">
        <div>
          <dl>
            <dt class="light">
              着手金
            </dt>
            <dd class="text-orange">
              <span><em>0</em>円</span>
            </dd>
          </dl>
          <dl>
            <dt class="light">
              相談料
            </dt>
            <dd class="text-orange">
              <span><em>0</em>円</span>
            </dd>
          </dl>
          <dl>
            <dt class="light">
              弁護士<br>報酬
            </dt>
            <dd class="text-orange">
              成功報酬制
            </dd>
          </dl>
        </div>
        <a class="st-button" href="#sc-form">
          お問い合わせはこちら
        </a>
      </div>
      <img src="~static/images/ref_woman01.png" alt="女性">
    </div>
  </section>
</template>
<style lang="scss" scoped>
h2 {
  font-size: 64px;
  font-weight: normal;
  width: 520px;
  > span {
    display: flex;
    align-items: flex-end;
    margin-bottom: 13px;
    > span {
      line-height: 1;
    }
  }
  em {
    width: 164px;
    height: 70px;
    background-color: #f6f7f8;
    display: inline-block;
    padding: 8px 18px;
    box-sizing: border-box;
    font-size: 18px;
    font-weight: normal;
    box-shadow: 2px 2px 2px rgba(0,0,0,0.16);
    margin-right: 14px;
    span {
      font-size: 20px;
      font-weight: bold;
    }
  }
  strong {
    font-size: 125px;
    line-height: 1;
  }
}
.st-main {
  padding: 50px 0 64px;
  background-image: url(~static/images/bg_main01.jpg);
  background-size: cover;
  min-width: 1000px;
  > div {
    width: 965px;
    margin: 0 auto;
    position: relative;
    > p {
      font-size: 24px;
      font-weight: bold;
      line-height: 1;
      margin: 10px 0 20px;
      width: 520px;
      letter-spacing: 0.05em;
    }
    > img {
      position: absolute;
      bottom: -64px;
      right: -20px;
    }
  }
}
.st-main__detail {
  width: 500px;
  display: flex;
  justify-content: space-between;
  > div {
    display: flex;
    flex-wrap: wrap;
    width: 260px;
    justify-content: space-between;
  }
  dl {
    display: inline-flex;
    border: 2px solid #00d0d4;
    border-radius: 5px;
    height: 65px;
    width: 120px;
    background-color: #fff;
  }
  dt {
    -ms-writing-mode: tb-rl;
    writing-mode: vertical-rl;
    color: #fff;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 42px;
    font-size: 16px;
  }
  dd {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: calc(100% - 42px);
    font-size: 28px;
    font-weight: bold;
    span {
      display: inline-flex;
      align-items: flex-end;
    }
    em {
      font-size: 60px;
      line-height: 1;
    }
  }
  dl:last-child {
    width: 100%;
    margin-top: 10px;
    dt {
      width: 70px;
    }
  }
  > a {
    width: 220px;
    height: 65px;
  }
}
@media screen and (max-width: 780px) {
  .st-main {
    min-width: auto;
    > div {
      width: 92.8%;
      z-index: 1;
      > p {
        width: 100%;
        letter-spacing: -0.05em;
      }
      > img {
        width: 50%;
        z-index: -1;
        right: -3vw;
      }
    }
  }
}
@media screen and (max-width: 680px) {
  .st-main {
    padding: 6.7vw 0 18vw;
    > div {
      > p {
        font-size: 4.8vw;
      }
      > img {
        width: 59.47vw;
      }
    }
  }
  .st-main__detail {
    width: 100%;
    flex-direction: column;
    > div {
      width: 55vw;
      margin-bottom: 5.3333vw;
    }
    > a {
      width: 55vw;
      height: 13.8vw;
    }
    dl {
      width: 25.324vw;
    }
    dt {
      font-size: 3.2vw;
      width: 11vw;
    }
    dd {
      font-size: 5.3333vw;
      em {
        font-size: 12vw;
      }
    }
  }
  h2 {
    font-size: 12vw;
    font-weight: normal;
    width: auto;
    > span {
      display: flex;
      align-items: flex-end;
      margin-bottom: 13px;
      > span {
        line-height: 1;
      }
    }
    em {
      width: auto;
      height: auto;
      background-color: #f6f7f8;
      display: inline-block;
      padding: 1.2vw 2.1vw;
      box-sizing: border-box;
      font-size: 4.26666vw;
      font-weight: normal;
      box-shadow: 2px 2px 2px rgba(0,0,0,0.16);
      margin-right: 1.18vw;
      line-height: 1.125;
      span {
        font-size: 4.26666vw;
        font-weight: bold;
      }
    }
    strong {
      font-size: 23vw;
      line-height: 1;
    }
  }
}
</style>
