<template>
  <section>
    <div class="st-title title light">
      <h1>増額しない場合、成功報酬は頂きません！</h1>
      <strong>※諸経費20,000円がかかります</strong>
    </div>
    <h2 class="text-blue">皆さんに安心していただける<br>料金プラン</h2>
    <p>
      弁護士法人ETCは交通事故の被害に遭われて、<br>
      困っているあなたが最小限のリスクで相談できるプランを作っています。
    </p>
    <div class="st-list_container">
      <ul>
        <li>
          <dl>
            <dt class="light">相談料</dt>
            <dd class="text-orange st-zero"><strong>0</strong>円</dd>
          </dl>
        </li>
        <li>
          <dl>
            <dt class="light">着手金</dt>
            <dd class="text-orange st-zero"><strong>0</strong>円</dd>
          </dl>
        </li>
        <li>
          <dl>
            <dt class="light">弁護士<br>報酬</dt>
            <dd class="text-orange"><em>成功<br>報酬制</em></dd>
          </dl>
        </li>
      </ul>
      <strong class="st-note orange">※費用は全て後払いになります。</strong>
    </div>
  </section>
</template>
<style lang="scss" scoped>
section {
  padding-bottom: 50px;
}
.st-title {
  display: flex;
  flex-direction: column;
  padding: 10px 0;
  h1 {
    font-size: 30px;
  }
  strong {
    font-size: 14px;
    font-weight: normal;
  }
}
h2 {
  text-align: center;
  font-size: 30px;
  margin: 30px 0;
}
p {
  text-align: center;
}
.st-list_container {
  width: 960px;
  margin: 0 auto;
}
ul {
  display: flex;
  justify-content: space-between;
  margin-top: 30px;
}
dl {
  border: solid 4px #00d0d3;
  display: flex;
  width: 300px;
  height: 100px;
}
dt {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  font-weight: bold;
  width: 100px;
  -webkit-writing-mode: vertical-rl;
    -ms-writing-mode: tb-rl;
        writing-mode: vertical-rl;
}
dd {
  display: flex;
  justify-content: center;
  align-items: center;
  width: calc(100% - 100px);
  font-weight: bold;
  font-size: 28px;
  line-height: 1;
  strong {
    font-size: 80px;
  }
  em {
    font-size: 40px;
  }
}
.st-zero {
  align-items: baseline;
  margin-top: 5px;
}
.st-note {
  width: 100%;
  display: block;
  margin-top: 20px;
  text-align: center;
  font-weight: normal;
  padding: 4px;
}
</style>
