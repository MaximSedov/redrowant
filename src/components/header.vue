<template>
  <section class="header">
    <el-row>
      <el-col :xs="24" :sm="24" :md="24" :lg="24" :xl="24">
        <div>
          <el-row class="navbar">
            <el-col :xs="1" :sm="1" :md="1" :lg="4" :xl="4"></el-col>
            <el-col :xs="4" :sm="2" :md="2" :lg="2" :xl="2" class="logo">

            </el-col>
            <el-col :xs="13" :sm="1" :md="1" :lg="4" :xl="8">

            </el-col>
            <el-col :xs="0" :sm="19" :md="19" :lg="10" :xl="6">

              <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal">
                <el-menu-item index="1"><a href="#main">Главная</a></el-menu-item>
                <el-menu-item index="2"><a href="#problems">Проблемы</a></el-menu-item>
                <el-menu-item index="3"><a href="#product">Продукт</a></el-menu-item>
                <el-menu-item index="4"><a href="#structure">Состав</a></el-menu-item>
              </el-menu>

            </el-col>

            <el-col class="menu_button" :xs="5" :sm="4" :md="0" :lg="0" :xl="0">
              <el-button @click="drawer = true" type="primary">
                <i class="el-icon-menu"></i>
              </el-button>
            </el-col>

            <el-col :xs="1" :sm="1" :md="1" :lg="4" :xl="4"></el-col>
          </el-row>
        </div>
      </el-col>
    </el-row>
  </section>
  <el-drawer show-close v-model="drawer" direction="ttb" size="100%">
    <div class=""><a @click="drawer = false" href="#main">Главная</a></div>
    <div class=""><a @click="drawer = false" href="#problems">Проблемы</a></div>
    <div class=""><a @click="drawer = false" href="#product">Продукт</a></div>
    <div class=""><a @click="drawer = false" href="#structure">Состав</a></div>
  </el-drawer>
</template>

<script>
export default {
  data() {
    return {
      activeIndex: '1',
      drawer: false
    }
  }
}
</script>

<style scoped lang="scss">
@import "../colors.scss";
.header {
  position: fixed;
  width: 100%;
  z-index: 100;
  height: 60px;
  color: $white;
  background-color: $white;
  .navbar {
    height: 60px;
    .el-menu {
      border: none;
      a {
        text-decoration: none;
      }
      &--horizontal > .el-menu-item.is-active {
        border-bottom: 2px solid $mainGreen;
        color: $mainGreen;
      }
      &--horizontal > .el-menu-item {
        font-size: 20px;
      }
    }
  }
  .logo {
    background-image: url("../assets/logo.png");
    background-position: center center;
    background-repeat: no-repeat;
    background-size: 50px 50px;
  }
}
.el-menu-item * {
  vertical-align: top !important;
}
.menu_button {
  display: flex;
  align-items: center;
  justify-content: center;
  .el-button {
    background-color: $mainGreen;
    border-color: $mainGreen;
  }
  .el-button:active {
    background-color: $mainGreen;
    border-color: $mainGreen;
  }
}
.el-drawer {
  div {
    margin-bottom: 30px;
  }
  a {
    text-decoration: none;
    color: $black;
    font-size: 60px;
  }
}
@media (min-width: 768px) {
  .menu_button {
    display: none;
  }
}
@media (max-width: 768px) {
  .el-menu {
    display: none;
  }
}
</style>
