<template>
  <el-container>
    <el-header>
      <el-row type="flex" :align="middle">
        <el-col :span="10" :offset="2">
          <img src="../assets/img/serios-logo.svg" alt class="header-image" />
        </el-col>
        <el-col :span="10" class="hidden-sm-and-down">
          <a class="header-nav" href="https://github.com/OpenSerios">Github</a>
          <a class="header-nav" href="#">Docs</a>
          <a class="header-nav" href="#">About</a>
          <!-- <el-menu class="topHeader" mode="horizontal">
            <el-menu-item index="1">Docs</el-menu-item>
            <el-menu-item index="2">Github</el-menu-item>
            <el-menu-item index="3">About</el-menu-item>
            <el-submenu index="4">
              <template slot="title">Language</template>
              <el-menu-item index="4-1">English</el-menu-item>
              <el-menu-item index="4-2">中文</el-menu-item>
            </el-submenu>
          </el-menu>-->
        </el-col>
      </el-row>
    </el-header>
    <el-main class="main">
      <el-row type="flex" :align="middle">
        <el-col :span="7" class="hidden-sm-and-down">
          <img src="../assets/img/main-left.svg" />
        </el-col>
        <el-col :lg="10" :xs="24">
          <h1>The standard for secure blockchain applications</h1>
          <p
            style="text-align: justify;"
          >Serios provides tools to write, deploy and operate decentralized applications. We also protect leading organizations by performing security audits on their systems and products.</p>
        </el-col>
        <el-col class="hidden-sm-and-down" :span="7">
          <img src="../assets/img/main-right.svg" class="center-image" />
        </el-col>
      </el-row>
      <el-row class="main_2" :align="middle">
        <el-col :xs="24" :md="{span:4,offset:6}">
          <img src="../assets/img/nervos-logo.svg" class="center-image mobile_image" />
        </el-col>
        <el-col :xs="24" :md="4">
          <img src="../assets/img/Rust.svg" class="center-image" />
        </el-col>
        <el-col :xs="24" :md="4">
          <img src="../assets/img/Community.svg" class="center-image" />
        </el-col>
      </el-row>
      <el-row>
        <el-col :span="20" :push="2" class="main_3">
          <el-row>
            <el-col :span="24">
              <h3 class="what_offer">What We Offer ?</h3>
            </el-col>
            <el-col :xs="{span:18,push:3}" :md="{span:6,push:3}">
              <img src="../assets/img/MAGi.png" style="margin-bottom:9px;" />
              <p class="content-title">MAGi</p>
              <p
                class="content-title"
              >A JS Engine for Developers to write JS Scripts for the Nervos Network, written in C.</p>
              <div class="content-main">
                <p>Leverage standard, tested, and community-reviewed Scripts.</p>
                <p>Only need Bytes level CKB Space comparing KB level.</p>
                <p>Reduce your attack surface by reusing audited code.</p>
                <p>Most popular Engine in the industry.</p>
              </div>
            </el-col>
            <el-col :xs="{span:18,push:3}" :md="{span:6,push:3}">
              <img src="../assets/img/sdk.png" />
              <p class="content-title">SDK</p>
              <p
                class="content-title"
              >A suite of tools to help you develop, test, upgrade, and deploy CKB Scripts.</p>
              <div class="content-main">
                <p>Easy bug-fixing and quick iterations via CKB Script upgrades.</p>
                <p>Interactive commands to accelerate local development.</p>
                <p>Seamless integration with Serios MAGi.</p>
                <p>Multi-network support.</p>
              </div>
            </el-col>
            <el-col :xs="{span:18,push:3}" :md="{span:6,push:3}">
              <img src="../assets/img/ide.png" style="margin-bottom:2px;" />
              <p class="content-title">Online IDE</p>
              <p
                class="content-title"
              >A real hacker IDE, help designers to do agile development.</p>
              <div class="content-main">
                <p>Swift,Simple,Smart.</p>
                <p>First OnlineIDE support Nervos.</p>
                <p>One click to compile, deploy, test the CKB Scripts.</p>
                <p>Interactive tutorial to assist your first dapp.</p>
              </div>
            </el-col>
          </el-row>
        </el-col>
      </el-row>
      <el-row>
        <el-col :md="{span:10,push:7}" :xs="{span:18,push:3}">
          <div class="evaluation">
            <p
              class="evaluation-text"
            >Serios is a development environment including tools making Scripts development faster and easier. Developers only need Bytes level CKB space comparing KB level and directly deploy JS code, making development more efficient.</p>
            <img src="../assets/img/daniel.jpg" style="width:80px;height:80px; border-radius:50%;" alt />
            <p style="font-size:18px;font-weight:600;margin:0px;">Daniel</p>
            <p style="font-size:16px;margin-top:5px;">Co-founder of Nervos</p>
          </div>
        </el-col>
      </el-row>
    </el-main>
    <el-divider></el-divider>
    <el-footer>
      <img src="../assets/img/serios-logo.svg" class="footer-image" />
      <p style="margin:0;">© 2019. All rights reserved.</p>
    </el-footer>
  </el-container>
</template>

<script>
export default {
  name: "index"
};
</script>

<style scoped>
.main {
  margin-top: 5rem;
}
.el-menu.el-menu--horizontal {
  border-bottom: 0px;
}
.el-menu--horizontal > .el-menu-item.is-active {
  border-bottom: 0px;
}
.el-divider--horizontal {
  margin-bottom: 0.3rem;
}
.el-button:focus,
.el-button:hover,
.el-button:active,
.el-button:visited {
  color: black;
}
.topHeader {
  float: right;
}
.header-image {
  float: left;
  margin-top: 0.45rem;
}
.main_2 {
  margin-top: 5rem;
}
.main_3 {
  margin-top: 5rem;
  background: rgba(32, 32, 38, 1);
  border-radius: 10px;
}
.what_offer {
  font-size: 24px;
  font-family: Helvetica;
  color: rgba(255, 255, 255, 1);
  line-height: 29px;
  margin-top: 3rem;
  margin-bottom: 4rem;
}
.content-title {
  /* height: 69px; */
  font-size: 16px;
  color: rgba(255, 255, 255, 1);
  line-height: 23px;
}
.content-main {
  margin-bottom: 5rem;
}

.evaluation {
  margin: 5rem 0;
  background: url("../assets/img/symbol.svg") no-repeat center;
}
.footer-image {
  margin: 0;
}

.header-nav {
  float: right;
  height: 60px;
  line-height: 60px;
  text-align: center;
  margin-left: 70px !important;
  color: black;
  font-size: 15px;
  font-weight: 400;
  border: 0;
  text-decoration: none;
}
.el-button + .el-button {
  margin-left: 0;
}
@media screen and (max-width: 992px) {
  .mobile_image {
    margin-bottom: 5px;
  }
  .content-main > p {
    color: rgba(255, 255, 255, 1);
    font-size: 14px;
  }
  .evaluation-text {
    color: rgba(0, 0, 0, 1);
    text-align: inherit;
  }
}
@media screen and (min-width: 992px) {
  .center-image {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
  }
  .content-main > p {
    margin: 1.5rem 10%;
    font-size: 14px;
    color: rgba(255, 255, 255, 1);
    line-height: 23px;
    text-align: left;
  }
  .evaluation-text {
    font-size: 20px;
    color: rgba(0, 0, 0, 1);
    line-height: 32px;
    text-align: justify;
  }
}
</style>
