<template>
  <div class="one">
    <div class="beijing">
      <div class="nav">
        <div class="w">
          <img src="../imgs/w.jpg" />
        </div>
        <div class="daohang">
          <ul>
            <li>
              <a href class="zi">我的</a>
              <div class="a"></div>
            </li>
            <li>
              <a href class="zi">系列</a>
            </li>
            <li>
              <a href class="zi">电影</a>
            </li>
            <li>
              <a href class="zi">首页</a>
            </li>
          </ul>
        </div>
        <div class="msg">
          <img src="../imgs/搜索.png" alt="">
          <img src="../imgs/铃铛.png" />
        </div>
      </div>
      <div class="wenzi">
        <p>播放时长：51分钟</p>
        <div class="er">
          <img src="../imgs/星星.png" alt="">
          <span>7.5</span>
          <span>第 14 集，第 8 季，真相意味着什么？</span>
        </div>
        <p style="font-size:180px;color:white;margin-top: 60px;margin-bottom: 30px;"><strong>行尸走肉</strong></p>
        <p>随着僵尸越来越多，同伴越来越少，凯罗尔跑进森林中与僵尸展示激烈打斗... <br>
           瑞克和摩根发现自己竟然进入僵尸包围圈..</p>
        <div class="wa" style="color:white">
            <div class="watch">
              <img src="../imgs/播放.png" alt="">
              <span>观看</span>
            </div>
            <div class="add">
              <img src="../imgs/添加.png" alt="">
              <span>添加</span>
            </div>
            
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "one"
};
</script>
<style scoped>
.one {
  height: 2305px;
}
.beijing {
  height: 2305px;
  background-image: url("../imgs/电影网站1.jpg");
}
li {
  display: inline-block;
  width: 500px;
  height: 200px;
  text-align: center;
  line-height: 200px;
  float: right;
}
a {
  text-decoration: none;
  color: aliceblue;
  font-size: 20px;
}
.wenzi{
  color: #a6a6a6;
  text-align: left;
  margin-left: 650px;
  line-height: 200px;
}
img {
  width: 196px;
  height: 205px;
  display: inline-block;
  float: left;
  margin-left: 200px;
}
.msg>img{
  width: 70px;
  height: 70px;
  margin-top: 98px;
}
.nav {
  display: flex;
  border-bottom: 10px solid rgba(200,200,200,0.1);
}
.w{
  flex: 2;
}
.daohang{
  flex: 3;
}
.msg{
  flex: 1
}
.wa{
  display: flex;
  width: 30%;
}
.watch>img,.add>img{
  width: 50px;
  height: 50px;
  margin-top: 74px;
}
.er>img{
  width: 50px;
  height: 50px;
  margin: 0px;
  margin-top: 70px;
}
.watch{
  flex: 1;
  background-color:#db1623;
  border-radius: 100px;
  margin-right: 50px;
}
.add{
  flex: 1;
  background-color: black;
  border-radius: 100px;
}

</style>
