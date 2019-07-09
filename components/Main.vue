<template>
  <section>
    <div class="st-left text-light">
      <div class="st-titlebox">
        <h1>
          <span class="st-subtitle">
            <em class="text-blue">保険会社</em>から<br>提示された
          </span>
          <span class="st-maintitle">
            <em class="text-blue">賠償金額</em>を<br><strong class="text-blue">無料診断</strong>
          </span>
        </h1>
        <p class="text-light">増額しなければ、成功報酬はいただきません</p>
      </div>
      <div class="st-apeal">
        <ul>
          <li class="st-zeromoney">
            <dl>
              <dt class="light">着手金</dt>
              <dd class="text-orange"><em>0</em>円</dd>
            </dl>
          </li>
          <li class="st-zeromoney">
            <dl>
              <dt class="light">相談料</dt>
              <dd class="text-orange"><em>0</em>円</dd>
            </dl>
          </li>
          <li class="st-successmoney">
            <dl>
              <dt class="light">弁護士<br>報酬</dt>
              <dd class="text-orange">成功報酬制</dd>
            </dl>
          </li>
        </ul>
        <a href="#" class="st-button">お問い合わせはこちら</a>
      </div>
    </div>
    <img src="~static/images/ref_woman01.png" alt="イメージ女性">
  </section>
</template>
<style lang="scss" scoped>
section {
  background-image: url(~static/images/bg_main01.jpg);
  display: flex;
  justify-content: center;
  padding:50px 70px 0 110px;
  min-width: 980px;
}
.st-titlebox{
  width: 600px;
  .st-subtitle {
    display: inline-block;
    background-color: #fff;
    font-weight: normal;
    padding: 5px 15px;
    box-shadow: 2px 2px 2px rgba(0,0,0,0.2);
    em {
      font-weight: bold;
    }
  }
  .st-maintitle {
    font-size: 60px;
    font-weight: normal;
    line-height: 1;
  }
  strong {
    font-size: 114px;
    line-height: 1.1;
  }
  p {
    font-size: 22.5px;
    width: 100%;
    font-weight: bold;
  }
}
.st-apeal {
  display: flex;
}
ul {
  display: flex;
  flex-wrap: wrap;
  width: 260px;
}
li {
  margin: 5px;
}
dl {
  height: 65px;
  width: 120px;
  display: flex;
  border:none;
  border-radius: 15px;
  dt {
    display: flex;
    width: 42px;
    justify-content: center;
    align-items: center;
    border: solid 2px #00d0d3;
    border-radius: 5px 0 0 5px;
    font-size: 16px;
    -webkit-writing-mode: vertical-rl;
    -ms-writing-mode: tb-rl;
    writing-mode: vertical-rl;
  }
  dd {
    display: flex;
    justify-content: center;
    width: calc(100% - 42px);
    border: solid 2px #00d0d3;
    border-radius: 0 5px 5px 0;
    background-color: #fff;
  }
}
.st-zeromoney {
  dd {
    align-items: baseline;
    font-size: 26px;
    font-weight: bold;
  }
  em {
    font-size: 50px;
  }
}
.st-successmoney {
  width: 100%;
  dl {
    width: 100%;
    dd {
      align-items: center;
      font-size: 28px;
      font-weight: bold;
    }
  }
}
.st-button {
  height: 50px;
  margin: 5px;
  padding: 5px 30px;
}
img {
  height: 100%;
}

</style>
