<template>
  <el-container>
    <el-header>
      <el-row type="flex" :align="middle">
        <el-col :span="10" :offset="2">
          <img src="../assets/Desktop.png" alt class="header-image" />
        </el-col>
        <el-col :span="10">
          <el-menu class="topHeader" mode="horizontal">
            <el-menu-item index="1">Products</el-menu-item>
            <el-menu-item index="2">Github</el-menu-item>
            <el-menu-item index="3">About</el-menu-item>
            <el-submenu index="4">
              <template slot="title">Language</template>
              <el-menu-item index="4-1">English</el-menu-item>
              <el-menu-item index="4-2">中文</el-menu-item>
            </el-submenu>
          </el-menu>
        </el-col>
      </el-row>
    </el-header>
    <el-main>
      
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script>
export default {
  name: "index"
};
</script>

<style scoped>
.el-menu.el-menu--horizontal {
  border-bottom: 0px;
}
.topHeader {
  float: right;
}
.header-image {
  float: left;
  margin-top: 0.45rem;
}
</style>
