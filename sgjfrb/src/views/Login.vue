<template>
  <div class="signi">
    <div class="sign_left">
      <div class="sign_logo">
        <img src="../../public/images/indexlogo.png" alt>
      </div>
      <p>解放日报社</p>
      <h4>干部人事数据库</h4>
      <form action class="sign">
        <div class="leba">
          <p></p>
          <input type="text" name="username" id="username" autofocus="autofocus" placeholder="用户名">
        </div>
        <div class="leba">
          <p class="ppp"></p>
          <input type="password" name="password" id="password" placeholder="密码">
        </div>
        <div class="error"></div>
        <div class="sign_btn">
          <button class="btn" type="button" id="logoin_btn">登录</button>
        </div>
      </form>
    </div>
    <div class="sign_right">
      <img src="../../public/images/indeximg.png" alt>
    </div>
  </div>
</template>

<script>
//import {LoginInit} from "@/js/init";
export default {
    mounted: function(){
        //LoginInit();
        console.log(this.$refs)
    }
}
</script>



<style>
* {
  list-style: none;
  padding: 0;
  margin: 0;
  text-decoration: none;
  box-sizing: border-box;
}

body,
h1,
h2,
h3,
h4,
h5,
h6,
p,
pre,
blockquote,
dl,
dt,
dd,
ul,
ol,
li,
form,
fieldset,
legend,
input,
textarea,
button,
th,
td {
  margin: 0;
  padding: 0;
}

.clear {
  background: none;
  border: 0;
  clear: both;
  display: block;
  float: none;
  font-size: 0;
  overflow: hidden;
  visibility: hidden;
  width: 0;
  height: 0;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

fieldset,
img {
  border: none;
}

caption,
th {
  font-weight: normal;
}

address,
cite,
dfn,
em,
var,
i {
  font-style: normal;
}

code,
kbd,
pre,
samp,
tt {
  font-family: "Courier New", Courier, monospace;
  white-space: normal;
}

ul,
ol {
  list-style: none outside;
}

caption,
th {
  text-align: left;
}

q:before,
q:after {
  content: "";
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: normal;
}

select,
input,
button,
textarea {
  font-size: 100%;
}

img {
  display: block;
}

.signi {
  min-width: 1350px;
  margin: 0 auto;
  min-height: 680px;
  background: #fff;
}

.sign_left {
  width: 400px;
  height: 680px;
  float: left;
  padding-left: 50px;
}

.sign_logo {
  width: 100%;
  margin-top: 70px;
}

.sign_left > p {
  margin-top: 78px;
  font-size: 18px;
  color: #777778;
}
.sign_left > h4 {
  margin-top: 22px;
  color: #9b1f2e;
  font-size: 40px;
}

.sign_right {
  float: left;
}

.sign_right img {
  width: 100%;
  height: 100%;
}
.sign_left .sign {
  margin-top: 77px;
}
.sign_left .leba {
  border-bottom: 2px solid #cecece;
  width: 309px;
  margin-top: 15px;
  overflow: hidden;
  padding-bottom: 11px;
  line-height: 40px;
}
.sign_left .leba input {
  border: none;
  display: block;
  float: left;
  margin-top: 10px;
  outline: none;
  margin-left: 20px;
  width: 186px;
  color: #bbb;
}
.sign_left .leba p {
  width: 15px;
  height: 15px;
  background-image: url(../../public/images/icon.png);
  background-position: -179px;
  background-repeat: no-repeat;
  background-size: auto 14px;
  float: left;
  margin-top: 12px;
}
.sign_left .leba .ppp {
  background: url(../../public/images/icon.png) no-repeat -98px;
  background-size: auto 14px;
}
.sign_left label {
  display: block;
  float: left;
  font-size: 12pt;
  color: #9d9d9e;
  line-height: 40px;
  margin-left: 18px;
  width: 48px;
}
.sign_left .error {
  width: 309px;
  margin-top: 17px;
  font-size: 12px;
  height: 12px;
  text-align: center;
  color: #000;
  font-weight: 700;
}
.sign .btn {
  background: #3a6287;
  color: #fff;
  width: 166px;
  height: 30px;
  display: block;
  margin: 0 auto;
  border: 0;
  outline: none;
}
.sign_btn {
  width: 309px;
  margin-top: 32px;
  cursor: pointer;
}
</style>

