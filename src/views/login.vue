<template>
  <div class="sb">
    <el-card class="box-card" shadow="hover">
      <div slot="header" class="clearfix">
        <span>登录</span>
      </div>
      <div class="ymb">
        <el-input v-model="input" placeholder="请输入内容"></el-input>
        <el-input
          placeholder="请输入密码"
          v-model="input"
          show-password
        ></el-input>
        <el-button type="primary">登录</el-button>
      </div>
    </el-card>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.sb {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
.box-card {
  width: 450px;
}
.ymb {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
</style>
