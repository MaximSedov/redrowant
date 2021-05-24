<template>
  <el-row class="problems" type="flex" align="middle" justify="center" id="problems">
    <el-col :xs="24" :sm="24" :md="22" :lg="22" :xl="14">

      <div class="problems_title">
        <span>Проблемы <br> сельского хозяйства</span>
      </div>

      <div class="problems_list">
        <el-row type="flex" align="middle" justify="center" :gutter="20">
          <el-col :xs="24" :sm="12" :md="8" :lg="8" :xl="8">
            <div class="problems_list--block">
              <div class="problem_title">Проблема №1</div>
              <div class="problem_text">Истощение и закисление почв</div>
            </div>
          </el-col>
          <el-col :xs="24" :sm="12" :md="8" :lg="8" :xl="8">
            <div class="problems_list--block">
              <div class="problem_title">Проблема №2</div>
              <div class="problem_text">Короткий период для выращивания и сбора урожая</div>
            </div>
          </el-col>
          <el-col :xs="24" :sm="12" :md="8" :lg="8" :xl="8">
            <div class="problems_list--block">
              <div class="problem_title">Проблема №3</div>
              <div class="problem_text">Недостаток пригодных для обработки земель</div>
            </div>
          </el-col>
        </el-row>
      </div>

      <div class="problems_banner">

        <div class="problems_banner_text">
          <br><span>«Земля РФ» <br> <span style="text-transform:uppercase;">поможет <span style="text-decoration:underline;">повысить</span> урожайность <br> и <span style="text-decoration:underline;">восстанновить</span> почву</span> </span>
        </div>

      </div>

    </el-col>
  </el-row>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
@import "../colors.scss";
.problems {
  margin-top: 60px;
  min-height: 100vh;
  &_title {
    font-size: 60px;
    margin-bottom: 10%;
    text-transform: uppercase;
    font-weight: 400;
    color: $black;
  }
  &_list {
    &--block {
      background-image: url("../assets/flag.png");
      background-size: 100% 100%;
      background-position: bottom center;
      position: relative;
      height: 340px;

      .problem_title {
        background-color: $red;
        font-size: 26px;
        position: absolute;
        width: 100%;
        width: 60%;
        color: $white;
        text-transform: uppercase;
        font-weight: bold;
        padding: 8px 0;
        border-radius: 10px;
        left: 50%;
        transform: translateX(-50%);
        box-shadow: 0px 3px 6px 4px rgba(216, 0, 39, 0.3);
      }
      .problem_text {
        position: absolute;
        text-align: left;
        font-size: 26px;
        width: 100%;
        width: 60%;
        color: $black;
        font-weight: bold;
        padding: 8px 0;
        border-radius: 5px;
        left: 50%;
        top: 20%;
        transform: translateX(-50%);
      }
    }
  }
  &_banner {
    margin-top: -70px;
    height: 288px;
    &_text {
      background-image: url("../assets/banner.png");
      background-size: 100% 100%;
      height: 100%;
      font-size: 35px;
      color: $white;
      font-weight: 200;
      text-align: left;
      padding-left: 5%;
    }
  }
}
@media (max-width: 768px) {
}
</style>
