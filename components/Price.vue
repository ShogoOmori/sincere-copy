<template>
  <section class="st-price">
    <div class="light title">
      <h2>増額しない場合、成功報酬は頂きません！</h2>
      <p>※諸経費20,000円がかかります</p>
    </div>
    <p><strong class="text-blue">皆さんに安心していただける<br>料金プラン</strong></p>
    <p>
      弁護士法人ETCは交通事故の被害に遭われて、<br>
      困っているあなたが最小限のリスクで相談できるプランを作っています。
    </p>
    <ul>
      <li>
        <dl>
          <dt class="light">
            相談料
          </dt>
          <dd class="text-orange">
            <span><em>0</em>円</span>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="light">
            着手金
          </dt>
          <dd class="text-orange">
            <span><em>0</em>円</span>
          </dd>
        </dl>
      </li>
      <li>
        <dl>
          <dt class="light">
            弁護士<br>報酬
          </dt>
          <dd class="text-orange">
            <strong>成功<br>報酬制</strong>
          </dd>
        </dl>
      </li>
    </ul>
    <p class="orange">
      ※費用は全て後払いになります。
    </p>
  </section>
</template>
<style lang="scss" scoped>
.st-price {
  margin-bottom: 80px;
  > p:nth-child(2) {
    margin-bottom: 35px;
  }
  > p {
    text-align: center;
    line-height: 1.75;
    strong {
      font-size: 30px;
    }
  }
  > p:last-child {
    margin: 0 auto;
    width: 960px
  }
}
.title {
  flex-direction: column;
  height: 100px;
  p {
    font-size: 14px;
  }
}
h2 {
  font-size: 30px;
}
ul {
  display: flex;
  width: 960px;
  margin: 35px auto 20px;
  justify-content: space-between;
}
li {
  width: 300px;
}
dl {
  display: flex;
  border: 4px solid #00d0d3;
  box-sizing: border-box;
  width: 100%;
  height: 120px;
}
dt {
  -ms-writing-mode: tb-rl;
  writing-mode: vertical-rl;
  width: 90px;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  font-weight: bold;
}
dd {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: calc(100% - 90px);
  font-size: 35px;
  font-weight: bold;
  span {
    display: inline-flex;
    align-items: flex-end;
  }
  strong {
    font-size: 42px;
    line-height: 1.2;
  }
  em {
    font-size: 76px;
    line-height: 1;
  }
}
@media screen and (max-width: 780px){
  .st-price {
    > p {
      width: 94%;
      margin: 0 auto;
      &:last-child {
        width: 93.33333%;
      }
    }
  }
  ul {
    flex-direction: column;
    width: 80%;
  }
  li {
    width: 100%;
  }
}
@media screen and (max-width: 680px) {
  .st-price {
    > p {
      font-size: 4.26666vw;
      strong {
        font-size: 4.8vw;
      }
      &:nth-child(2) {
        margin-bottom: 10.6666vw;
      }
      &:last-child {
        width: 93.33333%;
        font-size: 4.26666vw;
      }
    }
  }
  .title {
    p {
      font-size: 4.26666vw;
      font-weight: normal;
    }
  }
  h2 {
    font-size: 4.8vw;
  }
  ul {
    margin: 10.6666vw auto;
  }
  li {
    margin-bottom: 5.3333vw;
  }
  dl {
    height: 27.5vw;
  }
  dt {
    width: 20vw;
    font-size: 4.8vw;
  }
  dd {
    width: calc(100% - 20vw);
    font-size: 10.6666vw;
    strong {
      font-size: 10.6666vw;
    }
    em {
      font-size: 26vw;
    }
  }
}
</style>
