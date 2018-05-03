<template>
  <div class="app">
    <!-- <el-row>
      <el-col :span="24">
        <div class="grid-content bg-purple-dark"></div>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span="12"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="12"><div class="grid-content bg-purple-light"></div></el-col>
    </el-row>
    <el-row>
      <el-col :span="8"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple-light"></div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple"></div></el-col>
    </el-row> -->
    <!-- <el-row :gutter="100">
      <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
    </el-row>
    <el-row :gutter="20">
      <el-col :span="6"><div class="grid-content"></div></el-col>
    </el-row> -->
    <!-- <el-row :gutter="10" :type="flex" :align="top" :justify="start"> -->
      <!-- <el-col :span="5"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="5" :offset="5"><div class="grid-content bg-purple"></div></el-col> -->
    <!-- <el-col :xs="8" :sm="6" :md="4" :lg="3" :xl="1"><div class="grid-content bg-purple"></div></el-col>
    <el-col :xs="4" :sm="6" :md="8" :lg="9" :xl="11"><div class="grid-content bg-purple"></div></el-col>
    </el-row> -->
    <!--<el-container>-->
      <!--<el-header>header</el-header>-->
      <!--<el-main>man</el-main>-->
    <!--</el-container>-->
    <!--<br>-->
    <!--<el-container>-->
      <!--<el-header>Header</el-header>-->
      <!--<el-container>-->
        <!--<el-aside width="200px">Aside</el-aside>-->
        <!--<el-main>Main</el-main>-->
      <!--</el-container>-->
    <!--</el-container>-->

    <!--<br>-->
    <!--<el-container>-->
      <!--<el-header>Header</el-header>-->
      <!--<el-container>-->
        <!--<el-aside width="200px">Aside</el-aside>-->
        <!--<el-container>-->
          <!--<el-main>Main</el-main>-->
          <!--<el-footer>Footer</el-footer>-->
        <!--</el-container>-->
      <!--</el-container>-->
    <!--</el-container>-->
    <!--<br>-->
    <!--<el-container>-->
      <!--<el-header></el-header>-->
      <!--<el-container>-->
        <!--<el-aside width="200px" height="200px">Aside</el-aside>-->
        <!--<el-main>Main</el-main>-->
      <!--</el-container>-->
      <!--<el-footer>Footer</el-footer>-->
    <!--</el-container>-->
    <!--<el-container style="height: 500px; border: 1px solid #eee">-->
      <!--<el-aside width="200px" style="background-color: rgb(238, 241, 246)">-->
        <!--<el-menu :default-openeds="['1', '3']">-->
          <!--<el-submenu index="1">-->
            <!--<template slot="title"><i class="el-icon-message"></i>导航一</template>-->
            <!--<el-menu-item-group>-->
              <!--<template slot="title">分组一</template>-->
              <!--<el-menu-item index="1-1">选项1</el-menu-item>-->
              <!--<el-menu-item index="1-2">选项2</el-menu-item>-->
            <!--</el-menu-item-group>-->
            <!--<el-menu-item-group title="分组2">-->
              <!--<el-menu-item index="1-3">选项3</el-menu-item>-->
            <!--</el-menu-item-group>-->
            <!--<el-submenu index="1-4">-->
              <!--<template slot="title">选项4</template>-->
              <!--<el-menu-item index="1-4-1">选项4-1</el-menu-item>-->
            <!--</el-submenu>-->
          <!--</el-submenu>-->
        <!--</el-menu>-->
        <!--<el-menu>-->
          <!--<el-submenu index="1">-->
            <!--<template slot="title"><i class="el-icon-message">选项一</i></template>-->
            <!--<el-menu-item-group>-->
              <!--<el-menu-item index="1-1">选项1</el-menu-item>-->
              <!--<el-menu-item index="1-2">选项2</el-menu-item>-->
            <!--</el-menu-item-group>-->
          <!--</el-submenu>-->
          <!--<el-submenu index="2"></el-submenu>-->
        <!--</el-menu>-->
      <!--</el-aside>-->
      <!--<el-main>-->
        <!--<el-table :data="tableData">-->
          <!--<el-table-column prop="date" label="如期" width="140">-->
          <!--</el-table-column>-->
          <!--<el-table-column prop="name" label="姓名" width="120">-->
          <!--</el-table-column>-->
          <!--<el-table-column prop="address" label="地址">-->
          <!--</el-table-column>-->
        <!--</el-table>-->
      <!--</el-main>-->
    <!--</el-container>-->
    <!--<el-radio v-model="radio" disabled label="1">备选项</el-radio>-->
    <!--<el-radio v-model="radio" label="2">备选项</el-radio>-->
    <!--<input type="radio"/>-->
    <!--<el-radio-group v-model="radio">-->
      <!--<el-radio :label="3">选项一</el-radio>-->
      <!--<el-radio :label="6">选项二</el-radio>-->
      <!--<el-radio :label="9">选项三</el-radio>-->
    <!--</el-radio-group>-->
    <!--<el-radio-group v-model="radio" size="small">-->
      <!--<el-radio-button label="成都"></el-radio-button>-->
      <!--<el-radio-button label="路线"></el-radio-button>-->
      <!--<el-radio-button label="泸州"></el-radio-button>-->
    <!--</el-radio-group>-->
    <!--<el-checkbox v-model="checked" true-label="sb" false-label="pl" @change="myfunc">备选项</el-checkbox>-->
    <!--<el-checkbox :indeterminate="isIndeteminate" v-model="checkAll" @change="handleCheckAllChange">全选</el-checkbox>-->
    <!--<div style="margin: 15px 0;"></div>-->
    <!--<el-checkbox-group v-model="checkedCities" @change="handleCheckedCitiesChange">-->
      <!--<el-checkbox v-for="city in cities" :label="city" :key="city">{{city}}</el-checkbox>-->
    <!--</el-checkbox-group>-->
    <!--<el-input v-model="input" placeholder="请输入内容" clearable>-->
      <!--<i slot="suffix" class="el-icon-date el-input__icon"></i>-->
    <!--</el-input>-->
    <!--<el-input placeholder="站稳发" type="textarea" :autosize="{minRows: 2, maxRows: 4}"></el-input>-->
    <!--<el-input placeholder="请输入内容" v-model="input3">-->
      <!--<template slot="prepend">HTTP://</template>-->
    <!--</el-input>-->
    <!--<el-input placeholder="请输入内容" v-model="input3">-->
      <!--<template slot="append">.com</template>-->
    <!--</el-input>-->
    <!--<el-input placeholder="输入内容" v-model="input5"></el-input>-->
    <el-input placeholder="请输入内容" class="input-with-select">
      <el-select v-model="select" slot="prepend" placeholder="请选择">
        <el-option label="餐厅名" value="1"></el-option>
        <el-option label="订单号" value="2"></el-option>
        <el-option label="用户密码" value="3"></el-option>
      </el-select>
      <el-button slot="append" icon="el-icon-search"></el-button>
    </el-input>
  </div>
</template>

<script>
// import ElRow from 'element-ui/packages/row/src/row'
// import ElContainer from 'element-ui/packages/container/src/main'
// import ElMain from 'element-ui/packages/main/src/main'
// import ElAside from 'element-ui/packages/aside/src/main'
// import ElHeader from 'element-ui/packages/header/src/main'
// import ElSelect from 'element-ui/packages/select/src/select'

const cityOptions = ['上海', '北京', '广州', '深圳']
export default {
  components: {
    // ElSelect,
    // ElHeader,
    // ElAside,
    // ElMain,
    // ElContainer,
    // ElRow
  },
  name: 'App',
  // data: function () {
  //   const item = {
  //     date: '2016-05-02',
  //     name: '王小虎',
  //     address: '成都高新区'
  //   }
  //   return {
  //     tableData: Array(20).fill(item)
  //   }
  // }
  data: function () {
    // return {
    //   'radio': '3'
    // }
    // return {
    //   checked: true
    // }
    // return {
    //   checkAll: false,
    //   checkedCities: ['上海', '北京'],
    //   cities: cityOptions,
    //   isIndeteminate: true
    // }
    return {
      input: ''
    }
  },
  methods: {
    handleCheckAllChange (val) {
      this.checkedCities = val ? cityOptions : []
      this.isIndeteminate = false
    },
    handleCheckedCitiesChange (value) {
      console.log(value)
      let checkCount = value.length
      this.checkAll = checkCount === this.cities.length
      this.isIndeteminate = checkCount > 0 && checkCount < this.cities.length
    },
    myfunc (value) {
      console.log(value)
    }
  }
}

</script>

<style lang='scss'>
  // .el-row {
  //   margin-bottom: 20px;
  //   &:last-child {
  //     margin-bottom: 0;
  //   }
  // }
  // .el-col {
  //   border-radius: 4px;
  // }
  // .bg-purple-dark {
  //   background: #99a9bf;
  // }
  // .bg-purple {
  //   background: #d3dce6;
  // }
  // .bg-purple-light {
  //   background: #e5e9f2;
  // }
  // .grid-content {
  //   border-radius: 4px;
  //   min-height: 36px;
  // }
  // .row-bg {
  //   padding: 10px 0;
  //   background: #f9fafc;
  // }
  // .el-row {
  //   margin-bottom: 20px;
  //   &:last-child {
  //     margin-bottom: 0;
  //   }
  // }
  // .el-col {
  //   border-radius: 4px;
  // }
  // .bg-purple-dark {
  //   background: #99a9bf;
  // }
  // .bg-purple {
  //   background: #e5e9f2;
  // }
  // .bg-purple-light {
  //   background: #99a9bf;
  // }
  // .grid-content {
  //   border-radius: 4px;
  //   min-height: 36px;
  // }
  // .row-bg {
  //   padding: 10px 0;
  //   background-color: #f9fafc
  // }
  /*.el-header, .el-footer {*/
    /*background-color: #b3c0d1;*/
    /*color: #333;*/
    /*text-align: center;*/
    /*line-height: 60px;*/
  /*}*/
  /*.el-aside {*/
    /*background-color: #d3dce6;*/
    /*color: #333;*/
    /*text-align: center;*/
    /*line-height: 200px;*/
  /*}*/
  /*.el-main {*/
    /*background-color: #e9eef3;*/
    /*color: #333;*/
    /*text-align: center;*/
    /*line-height: 160px;*/
  /*}*/
  /*body > .el-container {*/
    /*margin-bottom: 40px;*/
  /*}*/
  /*.el-container:nth-child(5) .el-aside,*/
  /*.el-container:nth-child(6) .el-aside {*/
    /*line-height: 260px;*/
  /*}*/
  /*.el-container:nth-child(7) .el-aside {*/
    /*line-height: 320px;*/
  /*}*/
  /*.el-aside {*/
    /*background-color: #409eff;*/
  /*}*/
  .el-select {
    background-color: red;
  }
</style>
