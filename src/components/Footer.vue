<template>
  <div>
    <el-tabs :tab-position="tabPosition" class="footer-tabs">
      <el-tab-pane label="首页">首页</el-tab-pane>
      <el-tab-pane label="发现">发现</el-tab-pane>
      <el-tab-pane label="订单">订单</el-tab-pane>
      <el-tab-pane label="我的">我的</el-tab-pane>
    </el-tabs>
  </div>
</template>

<script>
  export default {
    name: "Footer",
    data() {
      return {
        tabPosition: 'top'
      };
    }
  }
</script>

<style>
  .footer-tabs{
    box-shadow: 0 -0.266667vw 0.533333vw rgba(0,0,0,.1);
  }
  .footer-tabs .el-tabs__nav{
    display: flex;
    justify-content: space-around;
    width: 100%;

  }
  .el-tabs__nav{
  background:none;
  }
  .footer-tabs .el-tabs__active-bar{
    background-color: #409eff00;
  }
  .footer-tabs .el-tabs__nav-wrap:after{
    background-color: #e4e7ed00;
  }
  .footer-tabs .el-tabs__content{
    display: none;
  }

</style>
