<template>
    <div class="home">
      <el-input
        placeholder="🔍搜索商家、商品名称"
        v-model="input1"
        :disabled="true">
      </el-input>
    </div>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped>
.home el-input{
  text-align: center;
}
</style>
