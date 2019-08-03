<template>
  <el-container>
    <el-header>
      <el-row type="flex" :align="middle">
        <el-col :span="10" :offset="2">
          <img src="../assets/serios-logo.svg" alt class="header-image" />
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
    <el-main class="main">
      <el-row type="flex" :align="middle">
        <el-col :span="7">
          <img src="../assets/main-left.svg" >
        </el-col>
        <el-col :span="10">
          <h1>The standard for secure blockchain applications</h1>
          <p style="text-align: justify;">Serios provides tools to write, deploy and operate decentralized applications. We also protect leading organizations by performing security audits on their systems and products.</p>
        </el-col>
        <el-col :span="7">
          <img src="../assets/main-right.svg" >
        </el-col>
      </el-row>
      <el-row class="main_2">
        <el-col :offset="6" :span="4">
          <img src="../assets/nervos-logo.svg">
        </el-col>
        <el-col :span="4">
          <img src="../assets/Rust.svg">
        </el-col>
        <el-col :span="4">
          <img src="../assets/Community.svg">
        </el-col>
      </el-row>
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
.main{
  margin-top:5rem;
}
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
.main_2{
  margin-top:5rem;
}
</style>
