<template>

  <el-row class="capacity" type="flex" align="middle" justify="center" id="main">
    <el-col :xs="24" :sm="24" :md="24" :lg="10" :xl="10">

      <div class="capacity_title">
        <h1> <span class="text--green">Повысьте </span> <br> урожайность</h1> <br><span class="text--subtitle">при тех же затратах</span>
        <span class="text--tag">в 1,5 раза</span>
      </div>

      <div class="capacity_advantages">
        <el-row type="flex" align="middle" justify="center" :gutter="20">
          <el-col :xs="24" :sm="8" :md="8" :lg="8" :xl="6">
            <div class="capacity_advantages--block">
              <div class="text">
                <div class="dot"></div><span style="font-weight:bold;"> Повышает</span><br>урожайность
              </div>
            </div>
          </el-col>
          <el-col :xs="24" :sm="8" :md="8" :lg="8" :xl="6">
            <div class="capacity_advantages--block">
              <div class="text">
                <div class="dot"></div><span style="font-weight:bold;"> Экологически</span><br>чистый продукт
              </div>
            </div>
          </el-col>
          <el-col :xs="24" :sm="8" :md="8" :lg="8" :xl="6">
            <div class="capacity_advantages--block">
              <div class="text">
                <div class="dot"></div><span style="font-weight:bold;"> Улучшает</span><br>качество плодов
              </div>
            </div>
          </el-col>
        </el-row>
      </div>

    </el-col>
  </el-row>

</template>

<script>
export default {}
</script>

<style scoped lang="scss">
@import "../colors.scss";
.capacity {
  height: 100vh;
  background-image: url("../assets/bg.png");
  background-size: 100% 100%;
  background-repeat: no-repeat;
  &_title {
    margin-top: -30%;
    position: relative;
    h1 {
      color: $black;
      text-transform: uppercase;
      font-size: 80px;
      font-weight: bold;
      .text--green {
        color: $mainGreen;
      }
    }
    .text--subtitle {
      text-transform: lowercase;
      color: $black;
      font-size: 40px;
      font-weight: bold;
      margin-top: 6%;
    }
    .text--tag {
      text-transform: uppercase;
      font-size: 35px;
      font-weight: bold;
      position: absolute;
      background-color: $mainGreen;
      top: 60%;
      right: 60px;
      clip-path: polygon(2% 0%, 100% 0%, 98% 100%, 0% 100%);
      padding: 5px 15px;
      border-radius: 10px 5px 10px 5px;
      color: $white;
    }
  }
  &_advantages {
    margin-top: 20px;
    &--block {
      display: flex;
      align-items: center;
      justify-content: center;
      .dot {
        background-color: $mainGreen;
        width: 6px;
        height: 6px;
        border-radius: 3px;
        position: absolute;
        top: 10px;
        left: 0;
        box-shadow: 0px 3px 6px 4px rgba(2, 147, 82, 0.2);
      }
      .text {
        position: relative;
        font-size: 20px;
        padding-left: 30px;
        text-align: left;
        font-weight: 500;
      }
    }
  }
}
@media (max-width: 768px) {
  .capacity {
    background-size: cover;
    background-position: center center;
  }
  .capacity_advantages--block {
    margin-top: 20px;
    .text {
      width: 180px;
      text-align: center;
    }
  }
  .capacity_title {
    h1 {
      font-size: 50px;
    }
    .text--tag {
      top: 50%;
      font-size: 25px;
    }
  }
}
@media (max-width: 500px) {
  .capacity_title {
    h1 {
      font-size: 40px;
    }
    .text--tag {
      top: 35%;
      right: 10px;
      font-size: 25px;
    }
  }
}
</style>
