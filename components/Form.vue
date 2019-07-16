<template>
  <section>
    <h1 class="title light">
      お問い合わせフォーム
    </h1>
    <form action="">
      <div class="st-name">
        <dl>
          <dt>
            <label for="comname">御社名</label><span>必須</span>
          </dt>
          <dd>
            <input id="comname" type="text" required>
          </dd>
        </dl>
        <dl>
          <dt>
            <label for="comphonetic">御社名フリガナ</label><span>必須</span>
          </dt>
          <dd>
            <input id="comphonetic" type="text" required>
          </dd>
        </dl>
      </div>
      <div class="st-name">
        <dl>
          <dt>
            <label for="hname">担当者名</label><span>必須</span>
          </dt>
          <dd>
            <input id="hname" type="text" required>
          </dd>
        </dl>
        <dl>
          <dt>
            <label for="hphonetic">担当者名フリガナ</label><span>必須</span>
          </dt>
          <dd>
            <input id="hphonetic" type="text" required>
          </dd>
        </dl>
      </div>
      <dl>
        <dt>
          <label for="email">メールアドレス</label><span>必須</span>
        </dt>
        <dd>
          <input id="email" type="email" required>
        </dd>
      </dl>
      <dl>
        <dt>
          <label for="tel">電話番号</label>
        </dt>
        <dd>
          <input id="tel" type="tel">
        </dd>
      </dl>
      <dl>
        <dt>
          <label for="matter">ご用件</label>
        </dt>
        <dd>
          <textarea id="matter" name="" cols="30" rows="10" />
        </dd>
      </dl>
      <button type="submit" name="example" value="送信" class="st-button">
        送信
      </button>
    </form>
  </section>
</template>
<style lang="scss">
form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
dl {
  margin-bottom: 30px;
}
span {
  padding: 0 10px;
  margin-left:10px;
  display: inline-block;
  line-height: 1.8;
  color: #fff;
  background-color: #0082D3;
}
input {
  width: 350px;
  height: 30px;
  border: solid 1px #000;
}
textarea {
  width: 350px;
  height: 150px;
  border: solid 1px #000;
}
.st-name {
  display: flex;
  input {
    margin-right: 10px;
  }
  margin-bottom: 40px;
}
button {
  width: 250px;
  height: 75px;
  margin-bottom: 50px;
  border: none;
}
</style>
