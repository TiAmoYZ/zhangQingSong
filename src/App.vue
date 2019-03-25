<template>
  <div class="app" id="app">
    <!-- 第一行 -->
    <el-row>
      <el-col :xs="24" :sm="24" :md="5" :lg="6" :xl="5" class="part">
        <PartOne></PartOne>
      </el-col>
      <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="8" class="part">
        <PartTwo></PartTwo>
      </el-col>
      <el-col :xs="24" :sm="24" :md="7" :lg="6" :xl="11" class="part">
        <PartThree></PartThree>
      </el-col>
    </el-row>
    <!-- 第二行 -->
    <el-row>
      <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" class="part">
        <PartFour></PartFour>
      </el-col>
      <el-col :xs="24" :sm="24" :md="8" :lg="8" :xl="8" class="part">
        <PartFive></PartFive>
      </el-col>
      <el-col :xs="24" :sm="24" :md="4" :lg="4" :xl="4" class="part">
        <PartSix></PartSix>
      </el-col>
      <el-col :xs="24" :sm="24" :md="4" :lg="4" :xl="4" class="part">
        <PartSeven></PartSeven>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import PartOne from "@/components/PartOne";
import PartTwo from "@/components/PartTwo";
import PartThree from "@/components/PartThree";
import PartFour from "@/components/PartFour";
import PartFive from "@/components/PartFive";
import PartSix from "@/components/PartSix";
import PartSeven from "@/components/PartSeven";
export default {
  name: "App",
  components: {
    PartOne,
    PartTwo,
    PartThree,
    PartFour,
    PartFive,
    PartSix,
    PartSeven
  }
};
</script>

<style>
body {
  background: #011128;
  color: #fff;
}
.app {
  width: 100%;
}
.part {
  padding: 20px;
}
.banner img {
  width: 100%;
  height: 80px;
}
.BMap_cpyCtrl,
.BMap_noprint,
.anchorBL {
  display: none !important;
}
</style>