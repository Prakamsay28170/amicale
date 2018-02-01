<template>
  <div id="FooterAmicale">
    <div class="row">
      <div class="footerPage">
        <el-row :gutter="0">
          <el-col :span="3" :offset="0">
            <h6>Mentions légales</h6>
          </el-col>
          <el-col :span="8" :offset="5">
            <h6>All Copyright&copy;2013-2018  Amicale de Fontaine-les-Ribouts<br>
            http://www.doyoubuzz.com/stephane-coulomb</h6>
          </el-col>
          <el-col :span="5" :offset="3">
            <h6>Developed by Stéphane COULOMB</h6>
          </el-col>
        </el-row>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'FooterAmicale',
  data: () => ({
  })
}
</script>
<style>
.footerPage {
  /*background-color: #c3e3f7;*/
}
.cv {
  padding-top: 0px;
}
</style>
