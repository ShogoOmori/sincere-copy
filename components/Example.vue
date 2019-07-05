<template>
  <section class="st-example">
    <h2 class="title light">
      <i><img src="~static/images/ref_man01.png" alt="男性"></i>交渉は私たちプロにお任せください！
    </h2>
    <p><strong class="text-blue">保険会社とは根本的に<br class="sp-view">異なる判断基準</strong></p>
    <p>交通事故の損害賠償請求は保険<br class="sp-view">会社に任せにしてしまうと、<br class="pc-view">適<br class="sp-view">正な賠償を受け取れない可能性<br class="sp-view">があります。</p>
    <section>
      <div class="st-compare">
        <h3>女性【専業主婦】<span>後遺障害等級12級</span></h3>
        <p aria-label="賠償金約480万円から">
          <span class="light">賠償金額</span>
          <em class="text-blue"><span>約480</span>万円</em>
        </p>
        <p aria-label="約570万円増額の約1050万円になりました。">
          <span class="blood">約570万円増額!!</span>
          <strong class="text-orange"><span>約</span><span>1,050</span>万円</strong>
        </p>
      </div>
      <ul>
        <li>
          <section>
            <h4 class="text-light">
              障害による損害額
            </h4>
            <table>
              <thead>
                <tr>
                  <th>項目</th>
                  <th>算定額(ご依頼前)</th>
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
                  <td>支払い済み</td>
                  <td>支払い済み</td>
                </tr>
                <tr>
                  <td class="light">
                    通院費
                  </td>
                  <td>26,460円</td>
                  <td>26,460円</td>
                </tr>
                <tr>
                  <td class="light">
                    休業損害<span>※1</span>
                  </td>
                  <td class="text-blue">
                    837,900円
                  </td>
                  <td class="text-light">
                    <strong>1,306,500円</strong>
                  </td>
                </tr>
                <tr>
                  <td class="light">
                    障害<br class="sp-view">慰謝料<span>※2</span>
                  </td>
                  <td class="text-blue">
                    867,900円
                  </td>
                  <td class="text-light">
                    <strong>1,348,000円</strong>
                  </td>
                </tr>
              </tbody>
              <tfoot>
                <tr class="orange">
                  <td>小計<span>A</span></td>
                  <td>1,732,260円</td>
                  <td><strong>2,680,960円</strong></td>
                </tr>
              </tfoot>
            </table>
          </section>
        </li>
        <li>
          <section>
            <h4 class="text-light">
              後遺障害による損害額
            </h4>
            <table>
              <thead>
                <tr>
                  <th>項目</th>
                  <th>算定額(ご依頼前)</th>
                  <th class="text-light">
                    算定額(ご依頼後)
                  </th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="light">
                    逸失利益
                  </td>
                  <td class="text-blue">
                    2,104,752円
                  </td>
                  <td class="text-light">
                    <strong>4,919,040円</strong>
                  </td>
                </tr>
                <tr>
                  <td class="light">
                    後遺障害<br>慰謝料
                  </td>
                  <td class="text-blue">
                    930,000円
                  </td>
                  <td class="text-light">
                    <strong>2,900,000円</strong>
                  </td>
                </tr>
              </tbody>
              <tfoot>
                <tr class="orange">
                  <td>小計<span>B</span></td>
                  <td>3,034,725円</td>
                  <td><strong>7,819,040円</strong></td>
                </tr>
              </tfoot>
            </table>
          </section>
        </li>
        <li>
          <section>
            <h4 class="text-light">
              損害賠償額
            </h4>
            <table>
              <thead>
                <tr>
                  <th>項目</th>
                  <th>算定額(ご依頼前)</th>
                  <th class="text-light">
                    算定額(ご依頼後)
                  </th>
                </tr>
              </thead>
              <tfoot>
                <tr class="orange">
                  <td>小計<span>A+B</span></td>
                  <td>1,732,260円</td>
                  <td><strong>2,680,960円</strong></td>
                </tr>
              </tfoot>
            </table>
          </section>
        </li>
      </ul>
      <img src="~static/images/ref_woman02.png" alt="女性">
    </section>
  </section>
</template>
<style lang="scss" scoped>
.st-example {
  margin-bottom: 80px;
  overflow: hidden;
  > p {
    text-align: center;
    font-size: 16px;
    margin-bottom: 35px;
    strong {
      font-size: 30px;
    }
  }
  > section {
    width: 960px;
    margin: 0 auto;
    position: relative;
    > img {
      position: absolute;
      right: -150px;
      bottom: -80px;
      z-index: -1;
    }
  }
}
.st-compare {
  display: flex;
  justify-content: space-between;
  margin-bottom: 40px;
  flex-wrap: wrap;
  width: 620px;
  p {
    display: flex;
    flex-direction: column;
    > span {
      display: inline-flex;
      justify-content: center;
      align-items: center;
      font-size: 16px;
      height: 30px;
    }
  }
  p:nth-child(2) {
    width: 150px;
    position: relative;
    em {
      font-size: 24px;
      margin-top: 10px;
      font-weight: bold;
      line-height: 1;
      display: flex;
      align-items: flex-end;
      justify-content: center;
      padding-bottom: 5px;
      border-bottom: 5px solid #00d0d3;
      position: relative;
      span {
        font-size: 32px;
      }
    }
    em::before {
      content: "";
      width: 5px;
      height: 17px;
      background-color: #00d0d3;
      display: block;
      position: absolute;
      margin: 0 auto;
      left: 0;
      right: 0;
      bottom: -22px;
    }
    em::after {
      content: "";
      display: block;
      width: 111px;
      height: 5px;
      background-color: #00d0d3;
      position: absolute;
      left: 50%;
      bottom: -22px;
    }
  }
  p:nth-child(2)::after {
    content: "";
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 16.5px 0 16.5px 17px;
    border-color: transparent transparent transparent #00cfd3;
    right: -53px;
    bottom: 7px;
  }
  p:last-child {
    width: 400px;
    strong {
      font-size: 46px;
      line-height: 1;
      display: flex;
      align-items: flex-end;
      justify-content: center;
      span {
        font-size: 90px;
      }
      span:first-child {
        font-size: 80px;
      }
    }
  }
}
h2 {
  i {
    display: grid;
    margin-left: -93px;
  }
}
h3 {
  margin-bottom: 10px;
  width: 100%;
}
h4 {
  font-size: 20px;
  margin-bottom: 16px;
  display: flex;
  align-items: flex-start;
}
h4::before {
  content: "";
  display: inline-block;
  margin-right: 8px;
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 13.5px 0 13.5px 13px;
  border-color: transparent transparent transparent #00cfd3;
}
ul {
  width: 620px;
}
li {
  margin-bottom: 40px;
}
li:last-child {
  margin-bottom: 0;
  h4 {
    font-size: 30px;
    line-height: 1;
  }
}
table {
  width: 100%;
  border-collapse: collapse;
  text-align: center;
  box-sizing: border-box;
  background-color: #fff;
  td {
    position: relative;
    span {
      position: absolute;
      top: 8px;
      right: 5px;
      font-size: 10px;
    }
  }
}
thead {
  background-color: #f6f7f7;
  th {
    font-size: 16px;
  }
  th:first-child {
    width: 112px;
  }
  th:last-child {
    border-right: 1px solid #f6f7f7;
  }
}
tbody {
  td {
    border-bottom: 1px dashed #00d0d4;
    font-size: 16px;
    strong {
      font-size: 20px;
    }
  }
  td.text-blue {
    padding: 20px 0;
  }
  td:first-child {
    border-bottom: 1px dashed #fff;
    padding: 8px;
  }
  td:last-child {
    border-right: 1px solid #00d0d4;
  }
  tr:last-child {
    td {
      border-bottom: 0;
    }
  }
}
tfoot {
  td {
    padding: 8px;
    font-size: 16px;
    strong {
      font-size: 20px;
    }
    span {
      right: auto;
      left: 65%;
    }
  }
  td:last-child {
    border-right: 1px solid #ffb400;
  }
}
@media screen and (max-width: 780px) {
  .st-example {
    > p {
      width: 94%;
      margin: 0 auto;
      text-align: left;
    }
    section {
      width: 100%;
    }
    > section {
      > img {
        width: 57%;
        opacity: 0.5;
        top: -100px;
      }
    }
    ul {
      width: 92.8%;
      margin: 0 auto;
    }
  }
  .st-compare {
    background-color: hsla(0, 0%, 100%, 0.8);
    width: 92.8%;
    margin: 0 auto;
    box-sizing: border-box;
  }
}
@media screen and (max-width: 680px) {
  .st-example {
    > p {
      font-size: 4.26666vw;
      strong {
        font-size: 4.8vw;
      }
      &:nth-child(2) {
        margin-bottom: 5.3333vw;
      }
    }
    > section {
      margin-top: 10.6666vw;
      > img {
        top: -60vw;
        right: -13vw;
      }
    }
    ul {
      width: 92.8%;
      margin: 0 auto;
    }
  }
  .st-compare {
    padding: 4.3vw 3.7vw 2.7vw;
    p {
      > span {
        font-size: 4.26666vw;
        height: 5.3333vw;
      }
      &:nth-child(2) {
        width: 25.6vw;
        em {
          font-size: 4.26666vw;
          span {
            font-size: 4.26666vw;
          }
          &:after {
            width: 17.334vw;
          }
        }
        &::after {
          border-width: 2.493333vw 0 2.493333vw 2.56533vw;
          right: -5.2vw;
          bottom: -0.6vw;
        }
      }
      &:last-child {
        width: 60vw;
        strong {
          font-size: 8vw;
          span {
            font-size: 15vw;
          }
          span:first-child {
            font-size: 8vw;
          }
        }
      }
    }
  }
  li:last-child {
    h4 {
      font-size: 4.26666vw;
    }
  }
  h2 {
    i {
      margin-left: 0;
      img{
        height: 16vw;
      }
    }
  }
  h3 {
    font-size: 4.26666vw;
    span {
      font-size: 3.2vw;
      margin-left: 2.7vw;
    }
  }
  h4 {
    font-size: 4.26666vw;
    align-items: center;
    &:before {
      border-width: 2.038666vw 0 2.038666vw 1.962vw;
    }
  }
  table {
    td {
      span {
        font-size: 2.4vw;
      }
    }
  }
  thead {
    th {
      font-size: 4.26666vw;
      height: 9.3333vw;
      font-weight: normal;
      &:first-child {
        width: 19.85vw;
      }
    }
  }
  tbody {
    td {
      font-size: 4.26666vw;
      &:first-child {
        padding: 2.13333vw 0;
      }
      strong {
        font-size: 5.3333vw;
      }
    }
  }
  tfoot {
    td {
      padding: 2.13333vw 0;
      font-size: 4.26666vw;
      span {
        top: 0;
        right: 0;
        left: 70%;
      }
      strong {
        font-size: 5.3333vw;
      }
    }
  }
}
</style>
