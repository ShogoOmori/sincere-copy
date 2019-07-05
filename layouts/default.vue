<template>
  <div>
    <nuxt />
  </div>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  list-style: none;
  text-decoration: none;
  font-style: normal;
}
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 14px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
main {
  display: block;
}
button {
  cursor: pointer;
}
.text-blue {
  color: #0082d3;
}
.blue {
  background-color: #0082d3;
  color: #fff;
}
.text-light {
  color: #00d0d3;
}
.light {
  background-color: #00d0d3;
  color: #fff;
}
.text-orange {
  color: #ffb400;
}
.orange {
  background-color: #ffb400;
  color: #fff;
}
.blood {
  background-color: #ff8800;
  color: #fff;
}
.title {
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 30px;
  font-weight: normal;
  position: relative;
  margin-bottom: 90px;
}
.title::after {
  content: "";
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 35px 35px 0 35px;
  border-color: #00d0d3 transparent transparent transparent;
  position: absolute;
  margin: 0 auto;
  left: 0;
  right: 0;
  bottom: -35px;
}
.st-button {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  background-color: #ffb400;
  box-shadow:0 5px 0 #ff7f00;
  border-radius: 5px;
  color: #fff;
  transition: 0.2 all;
}
.st-button:active {
  box-shadow: none;
}
.pc-view {
  display: block;
}
.sp-view {
  display: none;
}
@media screen and (max-width: 680px) {
  .pc-view {
    display: none;
  }
  .sp-view {
    display: inline-block;
  }
  .title {
    font-size: 4.8vw;
    font-weight: bold;
    height: 16vw;
    margin-bottom: 16vw;
    &::after {
      border-style: solid;
      border-width: 5.3333vw 5.3333vw 0 5.3333vw;
      border-color: #00cfd3 transparent transparent transparent;
      bottom: -5.3333vw;
    }
  }
}
</style>
