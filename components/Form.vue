<template>
  <section id="sc-form" class="st-form">
    <h2 class="title light">
      お問い合わせフォーム
    </h2>
    <form method="post">
      <div>
        <dl>
          <dt><label for="c-name">御社名<span class="required">必須</span></label></dt>
          <dd>
            <input id="c-name" type="text" required aria-required="true">
          </dd>
        </dl>
        <dl>
          <dt><label for="c-surname">御社名フリガナ<span class="required">必須</span></label></dt>
          <dd><input id="c-surname" type="text" required aria-required="true"></dd>
        </dl>
      </div>
      <div>
        <dl>
          <dt><label for="name">担当者名<span class="required">必須</span></label></dt>
          <dd><input id="name" type="text" required aria-required="true"></dd>
        </dl>
        <dl>
          <dt><label for="surname">担当者名フリガナ<span class="required">必須</span></label></dt>
          <dd><input id="surname" type="text" required aria-required="true"></dd>
        </dl>
      </div>
      <dl>
        <dt><label for="mail">メールアドレス<span class="required">必須</span></label></dt>
        <dd><input id="mail" type="email" required aria-required="true"></dd>
      </dl>
      <dl>
        <dt><label for="tel">電話番号</label></dt>
        <dd><input id="tel" type="tel"></dd>
      </dl>
      <dl>
        <dt><label for="textarea">ご用件</label></dt>
        <dd><textarea id="textarea" type="tel" /></dd>
      </dl>
      <button class="st-button" type="submit">
        送信
      </button>
    </form>
  </section>
</template>
<script>
export default {
  data: () => ({
  })
}
</script>
<style lang="scss" scoped>
.st-form {
  margin: 80px auto 0;
  padding-bottom: 80px;
  background-color: #f5f7f7;
}
h2 {
  font-weight: normal;
  margin-bottom: 70px;
  i {
    display: block;
    text-align: center;
  }
}
label {
  display: flex;;
  align-items: center;
}
form {
  width: 960px;
  padding: 40px 120px;
  box-sizing: border-box;
  margin: 0 auto;
  background-color: #fff;
  > div {
    display: flex;
    justify-content: space-between;
    margin-bottom: 35px;
  }
}
dl {
  width: 350px;
  margin: 0 auto 35px;
}
dl:last-child {
  margin-bottom: 40px;
}
input,
textarea {
  border: 1px solid #555555;
}
input {
  width: 350px;
  height: 30px;
  box-sizing: border-box;
}
textarea {
  width: 350px;
  height: 150px;
}
button {
  width: 260px;
  height: 66px;
  margin: 0 auto;
  border: none;
  display: block;
}
.required {
  width: 50px;
  height: 20px;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  background-color: #0082d3;
  color: #fff;
  font-size: 14px;
  margin-left: 10px;
}
@media screen and (max-width: 780px) {
  form {
    width: 93.3333%;
    padding: 40px;
    > div {
      flex-direction: column;
      margin-bottom: 0;
    }
  }
  dl {
    width: 100%;
  }
  input,
  textarea {
    width: 100%;
  }
}
@media screen and (max-width: 680px) {
  .st-form {
    margin: 21.3333vw auto 0;
    padding-bottom: 21.3333vw;
  }
  form {
    padding: 10.6666vw 13.2vw;
  }
  dl {
    margin-bottom: 5.3333vw;
    &:last-child {
      margin-bottom: 10.6666vw;
    }
  }
  dt {
    margin-bottom: 0.8vw;
  }
  button {
    width: 100%;
    font-size: 4.8vw;
    height: 16vw;
  }
}
</style>
