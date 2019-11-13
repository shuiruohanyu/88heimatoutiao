<template>
  <div class='login'>
    <!-- elementUI card卡片组件-->
    <el-card class='login-card'>
      <!-- 卡片内容 -->
      <div class='title'>
        <img src="../../assets/img/logo_index.png" alt="">
      </div>
      <!-- 表单 -->
      <el-form style="margin-top:30px">
        <!-- 一个表单域就是一个form-item -->
        <el-form-item>
          <!-- 放置表单组件  -->
          <!-- 手机号 -->
          <el-input></el-input>
        </el-form-item>
        <el-form-item>
          <!-- 验证码 和发送验证码 -->
          <el-input style='width:280px'></el-input>
          <el-button style="float:right" plain>发送验证码</el-button>
        </el-form-item>
         <el-form-item>
           <!-- 勾选同意框 -->
           <el-checkbox>我已阅读并同意用户协议及条款</el-checkbox>
         </el-form-item>
         <el-form-item>
           <el-button style="width:100%" type='primary'>登录</el-button>
         </el-form-item>
      </el-form>
    </el-card>
  </div>
</template>

<script>
export default {

}
</script>

<style lang='less' scoped>
  .login {
    background-image: url('../../assets/img/login_bg.jpg');
    background-size: cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    .login-card {
      width: 440px;
      height:360px;
      .title {
        text-align: center;
        img {
          height: 45px;
        }
      }
    }
  }
</style>
