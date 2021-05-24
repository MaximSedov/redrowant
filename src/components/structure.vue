<template>
  <el-row class="structure" type="flex" align="middle" justify="center" id="structure">
    <el-col :span="24">

      <div class="structure_title">
        <span>«ЗЕМЛЯ РФ»<br>состав препарата: </span>
      </div>
      <div class="structure_block--desktop">
        <el-row type="flex" align="middle" justify="center">
          <el-col class="structure_block" :xs="0" :sm="0" :md="0" :lg="12" :xl="12" style="height:200px;">

          </el-col>
          <el-col class="structure_block" :xs="24" :sm="24" :md="12" :lg="12" :xl="12" style="height:200px;">
            <div class="block_title"> <span>Полезные почвенные и флавобактерии</span> </div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Антагонисты патогенной флоры</span>
              </div>
            </div>
          </el-col>
        </el-row>

        <el-row type="flex" align="middle" justify="center">
          <el-col class="structure_block" :xs="24" :sm="24" :md="12" :lg="8" :xl="8">
            <div class="block_title"><span>Гуматы и фульваты</span></div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Комкуют и структурируют почву</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Обеспечивают доставку питательных веществ к корнями растений</span>
              </div>
            </div>
          </el-col>
          <el-col :xs="0" :sm="0" :md="0" :lg="8" :xl="8">
            <el-row type="flex" align="middle" justify="center">
              <el-col class="structure_block block-4" :xs="0" :sm="0" :md="0" :lg="8" :xl="8">

              </el-col>
              <el-col class="structure_block block-1" :xs="0" :sm="0" :md="0" :lg="8" :xl="8">

              </el-col>
              <el-col class="structure_block block-2" :xs="0" :sm="0" :md="0" :lg="8" :xl="8">

              </el-col>
            </el-row>
          </el-col>
          <el-col class="structure_block" :xs="24" :sm="24" :md="12" :lg="8" :xl="8">
            <div class="block_title"> <span>Торф</span> </div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Удерживает влагу</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Задерживает питательные вещетсва</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Является питанием для растений</span>
              </div>
            </div>
          </el-col>
        </el-row>
        <el-row type="flex" align="middle" justify="center">
          <el-col class="structure_block" :xs="24" :sm="24" :md="8" :lg="8" :xl="8" style="height:50px;">

          </el-col>
          <el-col class="structure_block" :xs="24" :sm="24" :md="8" :lg="8" :xl="8" style="height:50px;">

          </el-col>
          <el-col class="structure_block" :xs="24" :sm="24" :md="8" :lg="8" :xl="8" style="height:50px;">

          </el-col>
        </el-row>
        <el-row type="flex" align="middle" justify="center">
          <el-col class="structure_block" :xs="24" :sm="24" :md="12" :lg="8" :xl="8">
            <div class="block_title"> <span>Вихревая вода</span> </div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Повышает иммунитет растений</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Обеспечивает жизнедеятельность полезных почвенный бактерий</span>
              </div>
            </div>
          </el-col>
          <el-col :xs="0" :sm="0" :md="0" :lg="8" :xl="8">
            <el-row type="flex" align="middle" justify="center">
              <el-col class="structure_block block-5" :xs="0" :sm="0" :md="0" :lg="8" :xl="8">

              </el-col>
              <el-col class="structure_block" :xs="0" :sm="0" :md="0" :lg="8" :xl="8">

              </el-col>
              <el-col class="structure_block block-3" :xs="0" :sm="0" :md="0" :lg="8" :xl="8">

              </el-col>
            </el-row>
          </el-col>
          <el-col class="structure_block block-6" :xs="24" :sm="24" :md="12" :lg="8" :xl="8">
            <div class="block_title"> <span>Минеральные <br> удобрения и <br> микро элементы</span> </div>
          </el-col>
        </el-row>
      </div>

      <div class="structure_block--mobile">
        <el-row type="flex" align="middle" justify="center">
          <el-col class="structure_block block-5" :span="24">

          </el-col>
          <el-col class="structure_block" :span="24">
            <div class="block_title"> <span>Вирхевая вода</span> </div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Повышает иммунитет растений</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Обеспечивает жизнедеятельность полезных почвенный бактерий</span>
              </div>
            </div>
          </el-col>
          <el-col class="structure_block block-4" :span="24">

          </el-col>
          <el-col class="structure_block" :span="24">
            <div class="block_title"><span>Гуматы и фульваты</span></div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Комкуют и структурируют почву</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Обеспечивают доставку питательных веществ к корнями растений</span>
              </div>
            </div>
          </el-col>
          <el-col class="structure_block block-2" :span="24">

          </el-col>
          <el-col class="structure_block" :span="24">
            <div class="block_title"> <span>Торф</span> </div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Удерживает влагу</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Задерживает питательные вещетсва</span>
              </div>
              <div class="block">
                <div class="dot"></div>
                <span class="text">Является питанием для растений</span>
              </div>
            </div>
          </el-col>
          <el-col class="structure_block block-1" :span="24">

          </el-col>
          <el-col class="structure_block" :span="24">
            <div class="block_title"> <span>Полезные почвенные и флавобактерии</span> </div>
            <div class="block_subtitle">
              <div class="block">
                <div class="dot"></div>
                <span class="text">Антагонисты патогенной флоры</span>
              </div>
            </div>
          </el-col>
          <el-col class="structure_block block-3" :span="24">

          </el-col>
          <el-col class="structure_block block-6" :span="24">
            <div class="block_title"> <span>Минеральные удобрения и микро элементы</span> </div>
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
.structure {
  margin-top: 60px;
  margin-bottom: 60px;
  background-color: $white;
  background-image: url("../assets/structure.png");
  background-size: 100% 100%;
  background-position: bottom center;
  &_title {
    font-size: 60px;
    font-weight: bold;
    color: $black;
    text-align: left;
    margin-left: 5%;
    margin-bottom: 20px;
    margin-top: 60px;
  }

  &_block {
    height: 260px;
    position: relative;
    .block_title {
      text-align: left;
      width: 60%;
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      span {
        color: $black;
        font-size: 30px;
        font-weight: bold;
      }
    }
    .block_subtitle {
      font-size: 25px;
      color: $black;
      font-weight: 400;
      width: 60%;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translateX(-50%) translateY(-50%);
      .block {
        position: relative;
        width: 100%;
        text-align: left;
        .dot {
          background-color: $mainGreen;
          width: 6px;
          height: 6px;
          border-radius: 3px;
          position: absolute;
          top: 15px;
          left: 0;
          box-shadow: 0px 3px 6px 6px rgba(2, 147, 82, 0.2);
        }
        .text {
          padding-left: 30px;
          display: block;
        }
      }
    }
  }
  .block-1 {
    background-image: url("../assets/structure_1.png");
    background-repeat: no-repeat;
    background-position: top center;
  }
  .block-2 {
    background-image: url("../assets/structure_2.png");
    background-repeat: no-repeat;
    background-position: bottom right;
  }
  .block-3 {
    background-image: url("../assets/structure_3.png");
    background-repeat: no-repeat;
    background-position: top center;
  }
  .block-4 {
    background-image: url("../assets/structure_4.png");
    background-repeat: no-repeat;
    background-position: bottom left;
  }
  .block-5 {
    background-image: url("../assets/structure_5.png");
    background-repeat: no-repeat;
    background-position: top center;
  }
  .block-6 {
    background-image: url("../assets/minerals.png");
    background-repeat: no-repeat;
    background-position: bottom center;
  }
}
.structure_block--mobile {
  display: none;
}
@media (max-width: 1200px) {
  .structure {
    background-image: url("../assets/structure_text.png");
    background-size: 100% 50%;
    background-repeat: no-repeat;
  }
}
@media (max-width: 992px) {
  .structure {
    background-image: none;
  }
  .structure_block--mobile {
    display: block;
    .structure_block {
      min-height: 200px;
      .block_subtitle {
        width: 90%;
      }
      .block_title {
        width: 90%;
      }
    }

    .block-1 {
      background-image: url("../assets/structure_1.png");
      background-repeat: no-repeat;
      background-position: center center;
    }
    .block-2 {
      background-image: url("../assets/structure_2.png");
      background-repeat: no-repeat;
      background-position: center center;
    }
    .block-3 {
      background-image: url("../assets/structure_3.png");
      background-repeat: no-repeat;
      background-position: center center;
    }
    .block-4 {
      background-image: url("../assets/structure_4.png");
      background-repeat: no-repeat;
      background-position: center center;
    }
    .block-5 {
      background-image: url("../assets/structure_5.png");
      background-repeat: no-repeat;
      background-position: center center;
    }
    .block-6 {
      background-image: url("../assets/minerals.png");
      background-repeat: no-repeat;
      background-position: bottom center;
      height: 230px;
      background-size: 300px 100px;
    }
  }
  .structure_block--desktop {
    display: none;
  }
}
@media (max-width: 768px) {
  .structure_title {
    font-size: 40px;
  }
}
</style>
