<template>
  <section class="st-wrapper">
    <h1 class="st-main_title title light">
      交渉は私たちプロにお任せください！
    </h1>
    <div class="st-above">
      <h2 class="text-blue">
        保険会社とは根本的に異なる判断基準
      </h2>
      <p>
        交通事故の損害賠償請求は保険会社に任せにしてしまうと、<br>
        適正な賠償を受け取れない可能性があります。
      </p>
    </div>
    <div class="st-data_container">
      <div class="st-data">
        <p>女性【専業主婦】後遺障害等級12級</p>
        <div class="st-money_container">
          <dl class="st-money_before">
            <dt class="light">
              賠償金額
            </dt>
            <dd class="text-blue">
              約480<span class="st-yen_before">万円</span>
            </dd>
          </dl>
          <dl class="st-money_after">
            <dt>
              約570万円増額!!
            </dt>
            <dd class="text-orange">
              約1,050<span class="st-yen_after">万円</span>
            </dd>
          </dl>
        </div>
        <section>
          <h1 class="text-light">
            障害による損害額
          </h1>
          <table>
            <thead>
              <tr class="st-narrow">
                <th>
                  項目
                </th>
                <th>
                  算定額(ご依頼前)
                </th>
                <th class="text-light">
                  算定額(ご依頼後)
                </th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="light">
                  治療費
                </td>
                <td>
                  支払い済み
                </td>
                <td>
                  支払い済み
                </td>
              </tr>
              <tr>
                <td class="light">
                  通院費
                </td>
                <td>
                  26,460円
                </td>
                <td>
                  26,460円
                </td>
              </tr>
              <tr class="st-wide">
                <td class="light">
                  休業損害<span>※1</span>
                </td>
                <td class="text-blue">
                  837,900円
                </td>
                <td class="text-light">
                  <em>1,306,500円</em>
                </td>
              </tr>
              <tr class="st-wide">
                <td class="light">
                  障害慰謝料<span>※1</span>
                </td>
                <td class="text-blue">
                  867,900円
                </td>
                <td class="text-light">
                  <em>1,348,000円</em>
                </td>
              </tr>
            </tbody>
            <tfoot>
              <tr>
                <td class="orange">
                  小計<span>A</span>
                </td>
                <td class="orange">
                  1,732,260円
                </td>
                <td class="orange">
                  <em>2,680,960円</em>
                </td>
              </tr>
            </tfoot>
          </table>
        </section>
        <section>
          <h1 class="text-light">
            後遺障害による損害額
          </h1>
          <table>
            <thead>
              <tr class="st-narrow">
                <th>
                  項目
                </th>
                <th>
                  算定額(ご依頼前)
                </th>
                <th class="text-light">
                  算定額(ご依頼後)
                </th>
              </tr>
            </thead>
            <tbody>
              <tr class="st-wide">
                <td class="light">
                  逸失利益
                </td>
                <td class="text-blue">
                  2,104,752円
                </td>
                <td class="text-light">
                  <em>4,919,040円</em>
                </td>
              </tr>
              <tr class="st-wide">
                <td class="light">
                  後遺障害<br>慰謝料
                </td>
                <td class="text-blue">
                  930,000円
                </td>
                <td class="text-light">
                  <em>2,900,000円</em>
                </td>
              </tr>
            </tbody>
            <tfoot>
              <tr>
                <td class="orange">
                  小計<span>B</span>
                </td>
                <td class="orange">
                  3,034,725円
                </td>
                <td class="orange">
                  <em>7,819,040円</em>
                </td>
              </tr>
            </tfoot>
          </table>
        </section>
        <section>
          <h1 class="text-light">
            損害賠償額
          </h1>
          <table>
            <thead>
              <tr class="st-narrow">
                <th>
                  項目
                </th>
                <th>
                  算定額(ご依頼前)
                </th>
                <th class="text-light">
                  算定額(ご依頼後)
                </th>
              </tr>
            </thead>
            <tfoot>
              <tr>
                <td class="orange">
                  小計<span>A+B</span>
                </td>
                <td class="orange">
                  1,732,260円
                </td>
                <td class="orange">
                  <em>2,680,960円</em>
                </td>
              </tr>
            </tfoot>
          </table>
        </section>
      </div>
      <img src="~static/images/ref_woman02.png" alt="イメージ女性">
    </div>
  </section>
</template>
<style lang="scss" scoped>
.st-wrapper{
  padding-bottom: 70px;
  min-width: 1000px;
}
.st-main_title {
  &::before {
    content:'';
    width: 100px;
    height: 80px;
    background-image: url(~static/images/ref_man01.png);
    background-repeat: no-repeat;
    background-size: cover;
  }
}
.st-above {
  text-align: center;
  h2 {
    font-size: 30px;
  }
  p {
    font-size: 16px;
    margin-top: 30px;
  }
}
.st-data_container {
 display: flex;
 justify-content: center;
 .st-data {
   z-index: 10;
 }
 img {
   z-index: 0;
 }
}
.st-data {
  width: 600px;
  margin-left: 200px;
  margin-top: 30px;
  p {
    font-weight: bold;
  }
  h1 {
    font-size: 20px;
    position: relative;
    margin-left: 25px;
    &::before {
      content:'';
      width: 0;
      height: 0;
      position: absolute;
      left: -22px;
      top: 1px;
      border: 12px solid;
      border-color: transparent transparent transparent #00D0D3;
    }
  }
  section {
    margin-top: 40px;
  }
}
.st-money_container {
  display: flex;
  justify-content:space-between;
  dl {
    margin-top: 10px;
  }
  dt {
    display: flex;
    justify-content:center;
    align-items: center;
    width: 100%;
    height: 30px;
    font-size: 16px;
  }
}
.st-money_before {
 width: 150px;
 dd {
   margin-top: 10px;
   font-size: 30px;
   font-weight: bold;
   border-bottom: 5px solid #00D0D3;
   position: relative;
   &::before {
     content:'';
     width: 100px;
     height: 20px;
     position: absolute;
     left: 50%;
     bottom: -25px;
     border-left: 5px solid #00D0D3;
     border-bottom: 5px solid #00D0D3;
   }
   &::after {
      content:'';
      width: 0;
      height: 0;
      bottom: -42.5px;
      right: -55px;
      position: absolute;
      border: 20px solid;
      border-color: transparent transparent transparent #00D0D3;
   }
 }
}
.st-money_after {
  width: 400px;
  margin-left: 40px;
  dd {
    font-size: 89px;
    font-weight: bold;
  }
  dt {
    background-color: #FF8800;
    color: #fff;
    line-height: 100%;
  }
  .st-yen_after {
    font-size: 40px;
    -webkit-writing-mode: vertical-rl;
        -ms-writing-mode: tb-rl;
            writing-mode: vertical-rl;
  }
}
table {
  width: 100%;
  text-align: center;
  font-size: 16px;
  border-collapse: collapse;
  border-spacing: 2px;
  margin-top: 10px;
  tr {
    height: 45px;
  }
  td {
    position: relative;
    span {
      position: absolute;
      top: 7px;
      font-size: 10px;
    }
  }
}
tbody {
  tr:last-child {
    td{
      border-bottom: none;
    }
  }
  td {
    &:first-child {
      border-bottom: 1px solid #fff;
    }
    &:not(:first-child) {
      border-bottom: 1px dashed #00D0D3;
    }
    &:last-child {
      border-right : solid 1px #00D0D3;
    }
  }
}
.st-narrow {
  height: 25px;
}
.st-wide {
  height: 60px;
}
em {
  font-weight: bold;
  font-size: 20px;
}
</style>
