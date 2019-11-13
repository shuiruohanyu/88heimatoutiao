<template>
  <!-- 布局 -->
  <el-container>
    <!-- 左右布局 -->
    <el-aside>左侧内容</el-aside>
    <!-- 大容器 -->
    <el-container>
      <el-header>头部内容</el-header>
      <el-main>
        <!-- 二级路由容器 -->
        <router-view></router-view>
      </el-main>
    </el-container>
  </el-container>
</template>

<script>

export default {
  name: 'home',
  components: {

  }
}
</script>
