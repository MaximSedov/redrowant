<template>
  <el-row class="product" type="flex" align="middle" justify="center" id="product">
    <el-col :span="24">

      <div class="product_title">
        <span>Биопрепарат<br>«ЗЕМЛЯ РФ»:</span>
      </div>
      <el-row class="advantages">
        <el-col :xs="24" :sm="24" :md="18" :lg="18" :xl="18">
          <el-row>
            <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" class="advantages_block block_1">
              <div class="block_content">
                <span class="block_title">Экологически чистый продукт <br> <span class="block_subtitle">(торф + переработанный птичий помет)</span> </span>
              </div>
            </el-col>
            <el-col :xs="24" :sm="24" :md="16" :lg="16" :xl="16" class="advantages_block block_2">
              <div class="block_content">
                <el-row>
                  <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="">
                    <span class="block_title">Увеличивает на <br> <span class="green">30 - 50 %</span> </span>
                  </el-col>
                  <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="">
                    <span class="block_title"><br> <span class="block_subtitle">урожайность всех <br> видов с/х культур</span> </span>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" class="advantages_block block_3">
              <div class="block_content">
                <span class="block_title">pH препарата <br> <span class="green">7,9 - 8</span><br><span class="block_subtitle">Эффективен в закисленных почвах</span> </span>
              </div>
            </el-col>
            <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" class="advantages_block block_4">
              <div class="block_content">
                <span class="block_title">Повышает качество зерна <br> и класс зерновых</span>
              </div>
            </el-col>
            <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" class="advantages_block block_5">
              <div class="block_content">
                <span class="block_title">Восстанавливает гумусный слой <br> <span class="block_subtitle">(в т.ч. песчаные почвы и солончаки)</span> </span>
              </div>
            </el-col>
          </el-row>
        </el-col>

        <el-col :xs="24" :sm="24" :md="6" :lg="6" :xl="6" class="block_6">
          <div class="block_content">
            <span class="block_title">Снижает на <br> <span class="green">50 - 70 %</span> <span class="block_subtitle">использование минеральных удобрений </span></span>
          </div>
        </el-col>
      </el-row>
    </el-col>
  </el-row>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
@import "../colors.scss";
.product {
  margin-top: 60px;
  background-color: $white;
  margin-bottom: 60px;
  min-height: 100vh;
  &_title {
    font-size: 60px;
    font-weight: bold;
    color: $black;
    text-align: left;
    margin-left: 5%;
    margin-bottom: 20px;
    margin-top: 60px;
  }
  .advantages {
    &_block {
      height: 368px;
      position: relative;
      .block_content {
        position: absolute;
        top: 50%;
        left: 50%;
        width: 80%;
        transform: translateX(-50%) translateY(-50%);
      }
      .block_title {
        font-size: 40px;
        font-weight: bold;
      }
    }
    .block_1 {
      background-image: url("../assets/leaf.png");
      background-size: 100% 100%;
      color: $white;
      .block_subtitle {
        font-size: 30px;
        font-weight: 200;
      }
    }
    .block_2 {
      background-image: url("../assets/corn.png");
      background-size: 100% 100%;
      color: $black;
      .green {
        color: $mainGreen;
        font-size: 70px;
        font-weight: bold;
      }
      .block_subtitle {
        font-size: 35px;
        font-weight: 400;
      }
    }
    .block_3 {
      background-image: url("../assets/ph.png");
      background-size: 100% 100%;
      .block_subtitle {
        font-size: 30px;
        font-weight: 200;
      }
      .green {
        color: $mainGreen;
        font-size: 70px;
        font-weight: bold;
      }
    }
    .block_4 {
      background-image: url("../assets/ear.png");
      background-size: 100% 100%;
      color: $white;
    }
    .block_5 {
      background-image: url("../assets/earth.png");
      background-size: 100% 100%;
      color: $white;
      .block_subtitle {
        font-size: 30px;
        font-weight: 200;
      }
    }
    .block_6 {
      background-image: url("../assets/line.png");
      background-size: 100% 100%;
      position: relative;
      .block_content {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translateX(-50%) translateY(-80%);
      }
      .block_title {
        font-size: 40px;
        font-weight: bold;
        color: $white;
      }
      .block_subtitle {
        font-size: 35px;
        font-weight: 400;
      }
      .green {
        color: $green;
        font-size: 70px;
        font-weight: bold;
      }
    }
  }
}
@media (max-width: 768px) {
  .block_6 {
    display: none;
  }
  .product_title {
    font-size: 40px;
  }
  .green {
    font-size: 50px !important;
  }
}
</style>
