<template>
  <div class="two">
    <div class="up">
      <div class="next">
        <div class="zuijin">
          <img src="../imgs/指向.png" alt />
          <span style="font-size:50px;color:white;margin-top: 60px;margin-bottom: 30px;">
            <strong>最近流行的</strong>
          </span>
        </div>
      </div>
      <div class="xilie">
        <div>
          <img src="../imgs/火苗.png" />
          <span>流行</span>
        </div>
        <div>
          <img src="../imgs/灰星星.png" />
          <span>首映</span>
        </div>
        <div>
          <img src="../imgs/加号.png" />
          <span>最近加入</span>
        </div>
      </div>
    </div>
    <div class="zhong" style="color:white">
        <ul>
            <li style="background-color:#db1623">动作</li>
            <li>冒险</li>
            <li>动画</li>
            <li style="background-color:#db1623">传记</li>
            <li>犯罪</li>
            <li>喜剧</li>
            <li>记录</li>
            <li style="background-color:#db1623">戏剧</li>
        </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "two",
  components: {},
  data() {
    return {};
  }
};
</script>


<style scoped>
.two {
  width: 5000px;
  height: 2200px;
  background-color: #151518;
}
.up {
  display: flex;
  width: 4410px;
  height: 420px;
  margin: 0 auto;
  border-bottom: 10px solid rgba(200, 200, 200, 0.1);
}
.next {
  flex: 2;
}
.zuijin > img,
.xilie > div > img {
  width: 80px;
  height: 80px;
}
.xilie {
  flex: 1;
  display: flex;
  margin-top: 183px;
}
.xilie > div {
  flex: 1;
}
.zuijin {
  float: left;
  margin-top: 183px;
}
.zhong{
    width: 4410px;
    height: 120px;
    margin: 0 auto;
    margin-top: 160px;
}
.zhong ul li {
    display: inline-block;
    width: 430px;
    height: 120px;
    background-color: #1d1d21;
    border-radius: 100px;
    line-height: 120px;
    margin-right: 100px;
}

</style>