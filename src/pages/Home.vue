<template>
  <div class="home">
    <div class="home-top">
      <p><i class="el-icon-location"></i>青年北大街<i class="el-icon-caret-bottom"></i></p>
      <el-input
        placeholder="🔍搜索商家、商品名称"
        :disabled="true">
      </el-input>
    </div>
    <div class="types">
      <el-carousel trigger="click" height="180px" :autoplay="false" arrow="never">
        <el-carousel-item>
          <div class="wai-div">
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>美食</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>商超便利</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>水果</span>
              </a>
            </div>

            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>医药健康</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>浪漫鲜花</span>
              </a>
            </div>
          </div>
          <div class="wai-div">
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>跑腿代购</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>汉堡披萨</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>厨房生鲜</span>
              </a>
            </div>

            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>炸鸡炸串</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>地方菜系</span>
              </a>
            </div>
          </div>
        </el-carousel-item>
        <el-carousel-item>
          <div class="wai-div">
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>麻辣烫</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>速食简餐</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>地方小吃</span>
              </a>
            </div>

            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>大牌惠吃</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>米粉面馆</span>
              </a>
            </div>
          </div>
          <div class="wai-div">
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>包子粥店</span>
              </a>
            </div>
            <div class="tup">
              <a class="single-a">
                <img src="../assets/meis1.jpeg"/>
                <span>速食简餐</span>
              </a>
            </div>
          </div>
        </el-carousel-item>
      </el-carousel>
    </div>
    <div class="section">
      <div class="left-div">
        <h3>品质套餐</h3>
        <p>搭配齐全吃得好</p>
        <a>立即抢购<i class="el-icon-arrow-right"></i></a>
      </div>
      <div class="right-div">

        <img src="../assets/pinzhi.png"/></div>
    </div>
    <div class="vip">
      <p>
        <img src="../assets/queen.jpeg"/>
        <span class="supervip">超级会员</span>
        <span class="supervip1">每月领20元红包</span>
      </p>
      <p>立即开通<i class="el-icon-arrow-right"></i></p>
    </div>
    <div class="zhouwu-active">
      <el-carousel trigger="click" height="23.466667vw" arrow="never">
        <el-carousel-item>

          <img src="../assets/tu1.jpeg"/>
        </el-carousel-item>
        <el-carousel-item>

          <img src="../assets/tu2.jpeg"/>
        </el-carousel-item>
      </el-carousel>
      <div class="zizhi">资质证照</div>
    </div>
    <div class="shoper-list">
        <p class="tuijian">推荐商家</p>
      <ul>
        <li>综合排序<i class="el-icon-caret-bottom"></i></li>
        <li>距离最近</li>
        <li>品质联盟</li>
        <li>筛选</li>
      </ul>
      <div class="shoper-info">
        <div class="shoper-info-img">
          <img src="../assets/shop-img.jpeg"/>
        </div>
        <div class="shoper-info-right">
          <h3>
            <i class="brand">品牌</i>
            <span class="shoper-name">赛百味（市府恒隆店）</span>
          </h3>
          <p>
            <i class="el-icon-star-off"></i>
            <i class="el-icon-star-off"></i>
            <i class="el-icon-star-off"></i>
            <i class="el-icon-star-off"></i>
            <i class="el-icon-star-off"></i>
            <span>4.6</span>
            <span>月售233单</span>
            <i>蜂鸟专送</i>
          </p>
          <p>
            <span>￥20起送</span>
            <span>配送费￥3.5</span>
            <span>252m</span>
            <span>23分钟</span>
          </p>
          <p>
            <span>汉堡</span>
            <span>口碑人气好店</span>
          </p>
          <p>
            <i>减</i>
            <span>满30减2，满60减4，满90减6</span>
            <span>3个活动<i class="el-icon-caret-bottom"></i></span>
          </p>
          <p>
            <i>折</i>
            <span>折扣商品8折起</span>
          </p>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: "Home",
  }
</script>

<style>
  p, h3 {
    margin: 0;
  }

  .home .el-input {
    text-align: center;
    width: 95%;
    padding-top: 2vh;
  }

  .home .el-input.is-disabled .el-input__inner {
    text-align: center;
  }

  .home-top {
    height: 95px;
    background-image: linear-gradient(90deg, #0af, #0085ff);
    padding: 2.666667vw 3.733333vw 0;
  }

  .home-top p {
    text-align: left;
    margin: 0;
    color: #fff;
  }

  .tup {
    width: 20%;
  }

  .tup img {
    max-width: 100%;
  }

  .tup span {
    font-size: 0.32rem;
  }

  .single-a {
    display: inline-block;
    width: 13vw;
    height: 23vw;
  }

  .wai-div {
    display: flex;
  }

  .section {
    display: flex;
    justify-content: space-around;
    background: linear-gradient(0deg, #f4f4f4 5%, #fafafa 95%);
    margin: 2vw;
  }

  .right-div img {
    width: 37.6vw;
    height: 25.066667vw;
  }

  .left-div h3, .left-div p, .left-div a {
    margin-top: 2.4vw;
    text-align: left;
  }

  .left-div p, .left-div a {
    font-size: .346667rem;
  }

  .left-div a {
    color: #af8260;
    display: inline-block;
    width: 100%;
  }

  .vip {
    height: 10.666667vw;
    background-size: 100%;
    background-image: linear-gradient(90deg, #ffefc4, #f3dda0);
    font-size: .293333rem;
    line-height: 10.666667vw;
    display: flex;
    justify-content: space-between;
    margin: 2vw;
    padding: 0 2vw;
    color: #644f1b;
  }

  .vip img {
    width: 4.533333vw;
    height: 4.533333vw;
    display: inline-block;
    vertical-align: text-bottom;
    margin: 0 2vw;
  }

  .supervip {
    font-size: .373333rem;
    font-weight: 700;
  }

  .supervip1:before {
    content: "";
    height: 0.7vw;
    width: 1vw;
    display: inline-block;
    vertical-align: middle;
    background-color: #644f1b;
    border-radius: 22px;
    margin: 0 1.066667vw;
  }
  .zhouwu-active,.zhouwu-active img{
    height: 23.466667vw;
    position: relative;
    margin: 2vw;
  }
  .zizhi{
    z-index: 9;
    position: absolute;
    bottom: .533333vw;
    right: .533333vw;
    width: 14.666667vw;
    height: 5.066667vw;
    line-height: 5.066667vw;
    text-align: center;
    background-color: rgba(0,0,0,.5);
    font-size: .266667rem;
    border-radius: 2.666667vw;
    color: #eee;
  }
  .tuijian{
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .tuijian:before,.tuijian:after{
    content: "";
    width: 5.333333vw;
    height: .266667vw;
    background-color: #999;
    display: block;
    margin: 0 3.466667vw;
  }
  .shoper-list ul{
    height: 5.066667vw;
    display: flex;
    justify-content: space-around;
    padding: 0;
  }
  .shoper-list ul li{
    float: left;
    list-style: none;
  }
  .shoper-info{
    display: flex;
  }
  .shoper-info-img img{
    width: 17.333333vw;
    height: 17.333333vw;
  }
  .shoper-info-right{
    text-align: left;
  }
  .shoper-name{
    color: #333;
    font-weight: 700;
    font-size: .4rem;
  }
  .brand{
    font-size: .586667rem;
  }
</style>
