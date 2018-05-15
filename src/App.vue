<template>
  <div class='app'>
    <!-- <el-row>
      <el-col :span='24'>
        <div class='grid-content bg-purple-dark'></div>
      </el-col>
    </el-row>
    <el-row>
      <el-col :span='12'><div class='grid-content bg-purple'></div></el-col>
      <el-col :span='12'><div class='grid-content bg-purple-light'></div></el-col>
    </el-row>
    <el-row>
      <el-col :span='8'><div class='grid-content bg-purple'></div></el-col>
      <el-col :span='8'><div class='grid-content bg-purple-light'></div></el-col>
      <el-col :span='8'><div class='grid-content bg-purple'></div></el-col>
    </el-row> -->
    <!-- <el-row :gutter='100'>
      <el-col :span='6'><div class='grid-content bg-purple'></div></el-col>
      <el-col :span='6'><div class='grid-content bg-purple'></div></el-col>
      <el-col :span='6'><div class='grid-content bg-purple'></div></el-col>
      <el-col :span='6'><div class='grid-content bg-purple'></div></el-col>
    </el-row>
    <el-row :gutter='20'>
      <el-col :span='6'><div class='grid-content'></div></el-col>
    </el-row> -->
    <!-- <el-row :gutter='10' :type='flex' :align='top' :justify='start'> -->
      <!-- <el-col :span='5'><div class='grid-content bg-purple'></div></el-col>
      <el-col :span='5' :offset='5'><div class='grid-content bg-purple'></div></el-col> -->
    <!-- <el-col :xs='8' :sm='6' :md='4' :lg='3' :xl='1'><div class='grid-content bg-purple'></div></el-col>
    <el-col :xs='4' :sm='6' :md='8' :lg='9' :xl='11'><div class='grid-content bg-purple'></div></el-col>
    </el-row> -->
    <!--<el-container>-->
      <!--<el-header>header</el-header>-->
      <!--<el-main>man</el-main>-->
    <!--</el-container>-->
    <!--<br>-->
    <!--<el-container>-->
      <!--<el-header>Header</el-header>-->
      <!--<el-container>-->
        <!--<el-aside width='200px'>Aside</el-aside>-->
        <!--<el-main>Main</el-main>-->
      <!--</el-container>-->
    <!--</el-container>-->

    <!--<br>-->
    <!--<el-container>-->
      <!--<el-header>Header</el-header>-->
      <!--<el-container>-->
        <!--<el-aside width='200px'>Aside</el-aside>-->
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
        <!--<el-aside width='200px' height='200px'>Aside</el-aside>-->
        <!--<el-main>Main</el-main>-->
      <!--</el-container>-->
      <!--<el-footer>Footer</el-footer>-->
    <!--</el-container>-->
    <!--<el-container style='height: 500px; border: 1px solid #eee'>-->
      <!--<el-aside width='200px' style='background-color: rgb(238, 241, 246)'>-->
        <!--<el-menu :default-openeds='['1', '3']'>-->
          <!--<el-submenu index='1'>-->
            <!--<template slot='title'><i class='el-icon-message'></i>导航一</template>-->
            <!--<el-menu-item-group>-->
              <!--<template slot='title'>分组一</template>-->
              <!--<el-menu-item index='1-1'>选项1</el-menu-item>-->
              <!--<el-menu-item index='1-2'>选项2</el-menu-item>-->
            <!--</el-menu-item-group>-->
            <!--<el-menu-item-group title='分组2'>-->
              <!--<el-menu-item index='1-3'>选项3</el-menu-item>-->
            <!--</el-menu-item-group>-->
            <!--<el-submenu index='1-4'>-->
              <!--<template slot='title'>选项4</template>-->
              <!--<el-menu-item index='1-4-1'>选项4-1</el-menu-item>-->
            <!--</el-submenu>-->
          <!--</el-submenu>-->
        <!--</el-menu>-->
        <!--<el-menu>-->
          <!--<el-submenu index='1'>-->
            <!--<template slot='title'><i class='el-icon-message'>选项一</i></template>-->
            <!--<el-menu-item-group>-->
              <!--<el-menu-item index='1-1'>选项1</el-menu-item>-->
              <!--<el-menu-item index='1-2'>选项2</el-menu-item>-->
            <!--</el-menu-item-group>-->
          <!--</el-submenu>-->
          <!--<el-submenu index='2'></el-submenu>-->
        <!--</el-menu>-->
      <!--</el-aside>-->
      <!--<el-main>-->
        <!--<el-table :data='tableData'>-->
          <!--<el-table-column prop='date' label='如期' width='140'>-->
          <!--</el-table-column>-->
          <!--<el-table-column prop='name' label='姓名' width='120'>-->
          <!--</el-table-column>-->
          <!--<el-table-column prop='address' label='地址'>-->
          <!--</el-table-column>-->
        <!--</el-table>-->
      <!--</el-main>-->
    <!--</el-container>-->
    <!--<el-radio v-model='radio' disabled label='1'>备选项</el-radio>-->
    <!--<el-radio v-model='radio' label='2'>备选项</el-radio>-->
    <!--<input type='radio'/>-->
    <!--<el-radio-group v-model='radio'>-->
      <!--<el-radio :label='3'>选项一</el-radio>-->
      <!--<el-radio :label='6'>选项二</el-radio>-->
      <!--<el-radio :label='9'>选项三</el-radio>-->
    <!--</el-radio-group>-->
    <!--<el-radio-group v-model='radio' size='small'>-->
      <!--<el-radio-button label='成都'></el-radio-button>-->
      <!--<el-radio-button label='路线'></el-radio-button>-->
      <!--<el-radio-button label='泸州'></el-radio-button>-->
    <!--</el-radio-group>-->
    <!--<el-checkbox v-model='checked' true-label='sb' false-label='pl' @change='myfunc'>备选项</el-checkbox>-->
    <!--<el-checkbox :indeterminate='isIndeteminate' v-model='checkAll' @change='handleCheckAllChange'>全选</el-checkbox>-->
    <!--<div style='margin: 15px 0;'></div>-->
    <!--<el-checkbox-group v-model='checkedCities' @change='handleCheckedCitiesChange'>-->
      <!--<el-checkbox v-for='city in cities' :label='city' :key='city'>{{city}}</el-checkbox>-->
    <!--</el-checkbox-group>-->
    <!--<el-input v-model='input' placeholder='请输入内容' clearable>-->
      <!--<i slot='suffix' class='el-icon-date el-input__icon'></i>-->
    <!--</el-input>-->
    <!--<el-input placeholder='站稳发' type='textarea' :autosize='{minRows: 2, maxRows: 4}'></el-input>-->
    <!--<el-input placeholder='请输入内容' v-model='input3'>-->
      <!--<template slot='prepend'>HTTP://</template>-->
    <!--</el-input>-->
    <!--<el-input placeholder='请输入内容' v-model='input3'>-->
      <!--<template slot='append'>.com</template>-->
    <!--</el-input>-->
    <!--<el-input placeholder='输入内容' v-model='input5'></el-input>-->
    <!--<el-input placeholder='请输入内容' class='input-with-select'>-->
      <!--<el-select v-model='select' slot='prepend' placeholder='请选择'>-->
        <!--<el-option label='餐厅名' value='1'></el-option>-->
        <!--<el-option label='订单号' value='2'></el-option>-->
        <!--<el-option label='用户密码' value='3'></el-option>-->
      <!--</el-select>-->
      <!--<el-button slot='append' icon='el-icon-search'></el-button>-->
    <!--</el-input>-->
    <!--<el-row class='demo-autocomplete'>-->
      <!--<el-col :span='12'>-->
        <!--<div class='sub-title'>激活即列出输入建议</div>-->
        <!--<el-autocomplete-->
          <!--class='inline-input'-->
          <!--v-model='state1'-->
          <!--:fetch-suggestions='querySearch'-->
          <!--placeholder='请输入内容'-->
          <!--@select='handleSelect'/>-->
      <!--</el-col>-->
    <!--</el-row>-->
    <!--<el-autocomplete-->
      <!--popper-class='my-autocomplete'-->
      <!--v-model='state1'-->
      <!--:fetch-suggestions='querySearch'-->
      <!--placeholder='请输入内容'-->
      <!--@select='handleSelect'>-->
      <!--<i class='el-icon-edit el-input__icon' slot='suffix' @click='hanlde'></i>-->
      <!--<template slot-scope='{ item }'>-->
        <!--<div class='name'>{{item.value}}</div>-->
        <!--<span class='addr'>{{item.address}}</span>-->
      <!--</template>-->
    <!--</el-autocomplete>-->
    <!--<el-autocomplete-->
      <!--popper-class='my-autocomplete'-->
      <!--v-model='state1'-->
      <!--:fetch-suggestions='querySearchAsyn'-->
      <!--placeholder='请输入内容'-->
      <!--@select='handleSelect'>-->
    <!--</el-autocomplete>-->
    <!--<el-input v-model="input" placeholder="请输入内容">-->
      <!--<i class="el-icon-date" slot="prepend"></i>-->
    <!--</el-input>-->
    <!--<el-input-number v-model="num1" :step="2" :controls="false" controls-position="left" @change="handleChange" :min="1" :max="10" label="描述性文字"></el-input-number>-->
    <!--<el-select v-model="value1" multiple placeholder="请选择" @change="change">-->
      <!--<el-option v-for="item in items" :value="item.value" :key="item.lable" :label="item.value"></el-option>-->
    <!--</el-select>-->
    <!--<el-select v-model="value2" multiple placeholder="请选择">-->
      <!--<el-option v-for="item in items" :value="item.value" :key="item.lable" :label="item.value"></el-option>-->
    <!--</el-select>-->
    <!--<el-select v-model="value" placeholder="请选择">-->
      <!--<el-option-->
        <!--v-for="item in cities"-->
        <!--:key="item.value"-->
        <!--:label="item.label"-->
        <!--:value="item.value">-->
        <!--<span style="float: left">{{item.label}}</span>-->
        <!--<span style="float: right; color: red; font-size: 13px">{{item.value}}</span>-->
      <!--</el-option>-->
    <!--</el-select>-->
    <!--<el-select :popper-append-to-body="false" v-model="value" auto-complete="on" multiple :collapse-tags="true" placeholder="请选择">-->
      <!--<el-option-group-->
        <!--v-for="group in options3"-->
        <!--:key="group.label"-->
        <!--:label="group.label">-->
        <!--<el-option-->
          <!--v-for="item in group.options"-->
          <!--:key="item.value"-->
          <!--:label="item.label"-->
          <!--:value="item.value">-->
        <!--</el-option>-->
      <!--</el-option-group>-->
    <!--</el-select>-->
    <!--<el-cascader-->
      <!--:options="options"-->
      <!--v-model="selectedOptions"-->
      <!--expand-trigger="hover"-->
      <!--filterable-->
      <!--@change="handleChange"></el-cascader>-->
    <!--<el-switch-->
      <!--v-model="value"-->
      <!--active-text="按年付费"-->
      <!--inactive-text="按月付费">-->
    <!--</el-switch>-->
    <!--<el-slider :step="10" v-model="value" :show-stops="true" :show-input="true"></el-slider>-->
    <!--<el-slider v-model="value" range :show-stops="true" :max="10"></el-slider>-->
    <!--<el-slider-->
      <!--v-model="value"-->
      <!--:vertical="true"-->
      <!--height="200px"-->
      <!--label="plum"></el-slider>-->
    <!--<el-time-select-->
      <!--v-model="value"-->
      <!--:picker-options="{-->
        <!--start: '08:30',-->
        <!--step: '00:15',-->
        <!--end: '18:00'-->
      <!--}"></el-time-select>-->
    <!--<el-time-select-->
      <!--v-model="value1"-->
      <!--:picker-options="{-->
        <!--start: '08:30',-->
        <!--step: '00:15',-->
        <!--end: '18:00',-->
        <!--minTime: value-->
      <!--}"></el-time-select>-->
    <!--<el-time-picker-->
      <!--v-model="value"-->
      <!--:picker-options="{selectableRange: '18:30:00 - 20:00:00'}"-->
      <!--placeholder="任一时间点"-->
      <!--arrow-control>-->
    <!--</el-time-picker>-->
    <!--<el-time-picker-->
      <!--:is-range="true"-->
      <!--v-model="value"-->
      <!--range-separator="至"-->
      <!--start-placeholder="开始时间"-->
      <!--end-placeholder="结束时间"-->
      <!--:editable="true"-->
      <!--align="center">-->
    <!--</el-time-picker>-->
    <!--<el-date-picker-->
      <!--v-model="value"-->
      <!--align="right"-->
      <!--type="date"-->
      <!--:picker-options="options"-->
      <!--placeholder="选择日期"></el-date-picker>-->
    <!--<el-date-picker-->
      <!--v-model="value"-->
      <!--type="week"-->
      <!--format="yyyy第 WW 周"-->
      <!--placeholder="选择周"></el-date-picker>-->
    <!---->
    <!--<el-date-picker-->
      <!--type="dates"-->
      <!--v-model="value"-->
      <!--placeholder="选择多个日期">-->
    <!--</el-date-picker>-->
    <!--<el-date-picker-->
      <!--v-model="value"-->
      <!--type="daterange"-->
      <!--range-separator="至"-->
      <!--start-placeholder="开始日期"-->
      <!--unlink-panels-->
      <!--:picker-options="options"-->
      <!--end-placeholder="结束日期">-->
    <!--</el-date-picker>-->
    <!--<el-date-picker-->
      <!--v-model="value"-->
      <!--type="datetime"-->
      <!--placeholder="选择日期"-->
      <!--format="yyyy 年 MM 月 dd 日"-->
      <!--:default-time="['00:00:00', '23:59:59']">-->
    <!--</el-date-picker>-->
    <!--<div>{{value}}</div>-->
    <!--<el-upload-->
      <!--class="upload-demo"-->
      <!--action="https://jsonplaceholder.typicode.com/posts/"-->
      <!--:on-preview="handlePreview"-->
      <!--:on-remove="handlePreview"-->
      <!--:before-remove="beforeRemove"-->
      <!--:multiple="true"-->
      <!--:limit="3"-->
      <!--list-type="picture"-->
      <!--:on-exceed="handleExceed"-->
      <!--:file-list="fileList">-->
      <!--<el-button size="small" type="primary">点击上传</el-button>-->
      <!--<div slot="tip" class="el-upload__tip">只能上传jpg/png文件，且不超过500kb</div>-->
    <!--</el-upload>-->
    <!--<el-upload-->
      <!--class="avatar-uploader"-->
      <!--action="https://jsonplaceholder.typicode.com/posts/"-->
      <!--:show-file-list="false"-->
      <!--:on-success="handleAvatarSuccess"-->
      <!--:before-upload="beforeAvatarUpload">-->
      <!--<img v-if="imageUrl" :src="imageUrl" class="avatar"/>-->
      <!--<i v-else class="el-icon-plus avatar-uploader-icon"></i>-->
    <!--</el-upload>-->
  <!--<el-rate-->
    <!--v-model="value"-->
    <!--:colors="['#99A9BF', '#F7BA2A', '#FF9900']"-->
    <!--:show-text="true">-->
  <!--</el-rate>-->
    <!--<el-rate-->
      <!--v-model="value"-->
      <!--disabled-->
      <!--:max="10"-->
      <!--:show-score="true"-->
      <!--text-color="#ff9900"-->
      <!--score-template="{value}">-->
    <!--</el-rate>-->
    <!--<el-color-picker-->
      <!--:show-alpha="true"-->
      <!--:predefine="colors"-->
      <!--v-model="color">-->
    <!--</el-color-picker>-->
    <!--<el-color-picker-->
      <!--v-model="color2">-->
    <!--</el-color-picker>-->
    <!--<el-transfer-->
      <!--v-model="value"-->
      <!--:data="data"></el-transfer>-->
    <!--<el-transfer-->
      <!--filterable-->
      <!--:filter-method="filterMethod"-->
      <!--filter-placeholder="请输入城市拼音"-->
      <!--:left-default-checked="[1]"-->
      <!--v-model="value"-->
      <!--:render-content="renderFunc"-->
      <!--:titles="['Souce', 'Target']"-->
      <!--:button-texts="['到左边', '到右边']"-->
      <!--:format="{-->
        <!--noChecked: '${total}',-->
        <!--hasChecked: '${checked}/${total}'-->
      <!--}"-->
      <!--:data="data">-->
      <!--<el-button slot="left-footer" size="small">操作</el-button>-->
      <!--<el-button slot="right-footer" size="small">操作</el-button>-->
    <!--</el-transfer>-->
    <!--<el-form :inline="true" ref="form" :model="form" label-width="80px">-->
      <!--<el-form-item label="活动名称">-->
        <!--<el-input v-model="form.name"></el-input>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="活动区域">-->
        <!--<el-select v-model="form.region" placeholder="请选择活动区域">-->
          <!--<el-option label="区域一" value="shanghai"></el-option>-->
          <!--<el-option label="区域二" value="beijing"></el-option>-->
        <!--</el-select>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="活动时间">-->
        <!--<el-col :span="11">-->
          <!--<el-date-picker type="date" placeholder="选择日期" v-model="form.date1" style="width: 100%"></el-date-picker>-->
        <!--</el-col>-->
        <!--<el-col class="line" :span="2">-</el-col>-->
        <!--<el-col :span="11">-->
          <!--<el-time-picker type="fixed-time" placeholder="选择时间" v-model="form.date2" style="width: 100%"></el-time-picker>-->
        <!--</el-col>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="配送时间">-->
        <!--<el-switch v-model="form.delivery"></el-switch>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="活动性质">-->
        <!--<el-checkbox-group v-model="form.type">-->
          <!--<el-checkbox label="美食/餐厅线上活动" name="type"></el-checkbox>-->
          <!--<el-checkbox label="地推活动" name="type"></el-checkbox>-->
          <!--<el-checkbox label="线下主题活动" name="type"></el-checkbox>-->
          <!--<el-checkbox label="单纯品牌活动" name="type"></el-checkbox>-->
        <!--</el-checkbox-group>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="特殊资源">-->
        <!--<el-radio-group v-model="form.resource">-->
          <!--<el-radio label="线上品牌商赞助"></el-radio>-->
        <!--</el-radio-group>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="活动形式">-->
        <!--<el-input type="textarea" v-model="form.desc"></el-input>-->
      <!--</el-form-item>-->
      <!--<el-form-item>-->
        <!--<el-button type="primary" @click="onSubmit">立即创建</el-button>-->
        <!--<el-button>取消</el-button>-->
      <!--</el-form-item>-->
    <!--</el-form>-->
    <!--<el-form :model="ruleForm" :rules="rules" ref="ruleForm" label-width="100px">-->
      <!--<el-form-item label="活动名称" prop="name">-->
        <!--<el-input v-model="ruleForm.name"></el-input>-->
      <!--</el-form-item>-->
    <!--</el-form>-->
    <!--<el-form :model="ruleForm" :status-icon="true" :rules="rules" ref="ruleForm" style="width: 100px">-->
      <!--<el-form-item label="密码" prop="pass">-->
        <!--<el-input type="password" v-model="ruleForm.pass" auto-complete="off"></el-input>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="确认密码" prop="checkPass">-->
        <!--<el-input type="password" v-model="ruleForm.checkPass" auto-complete="off"></el-input>-->
      <!--</el-form-item>-->
      <!--<el-form-item label="年龄" prop="age">-->
        <!--<el-input v-model.number="ruleForm.age"></el-input>-->
      <!--</el-form-item>-->
    <!--</el-form>-->
    <!--<el-form :model="forms" ref="forms" label-width="100px">-->
      <!--<el-form-item-->
        <!--prop="email"-->
        <!--label="邮箱"-->
        <!--:rules="[-->
          <!--{required: true, message: '请输入邮箱地址', trigger: 'blur'},-->
          <!--{type: 'email', message: '请输入正确的邮箱地址', trigger: ['blur', 'change']}-->
        <!--]">-->
        <!--<el-input v-model="forms.email"></el-input>-->
      <!--</el-form-item>-->
      <!--<el-form-item-->
        <!--v-for="(domain, index) in forms.domains"-->
        <!--:label="'域名' + index"-->
        <!--:key="domain.key"-->
        <!--:prop="'domains.' + index + '.value'"-->
        <!--:rules="{-->
          <!--required:true, message: '域名不能为空', trigger: 'blur'-->
        <!--}">-->
        <!--<el-input v-model="domain.value"></el-input><el-button @click.prevent="removeDomain(domain)">删除</el-button>-->
      <!--</el-form-item>-->
      <!--<el-form-item>-->
        <!--<el-button @click="addDomain">新增域名</el-button>-->
      <!--</el-form-item>-->
    <!--</el-form>-->
    <el-table
      :data="tableData"
      :stripe="true"
      border
      height="250"
      style="width: 100%">
      <el-table-column
        prop="date"
        label="日期"
        width="180">
      </el-table-column>
      <el-table-column
        prop="name"
        label="姓名"
        width="180">
      </el-table-column>
      <el-table-column
        prop="address"
        label="地址">
      </el-table-column>
      <el-table-column
        prop="tag"
        label="标签"
        width="100"
        :filters="[{text: '家', value: '家'}, {text: '公司', value: '公司'}]"
        :filter-method="filterTag"
        filter-placement="bottom-end">
        <template slot-scope="scope">
          <el-tag
            :type="scope.row.tag === '家' ? 'primary' : 'success'"
            :disable-transitions="true">{{scope.row.tag}}</el-tag>
        </template>
      </el-table-column>
    </el-table>
  </div>
</template>

<script>
// import ElRow from 'element-ui/packages/row/src/row'
// import ElContainer from 'element-ui/packages/container/src/main'
// import ElMain from 'element-ui/packages/main/src/main'
// import ElAside from 'element-ui/packages/aside/src/main'
// import ElHeader from 'element-ui/packages/header/src/main'
// import ElSelect from 'element-ui/packages/select/src/select'

// const cityOptions = ['上海', '北京', '广州', '深圳']

// import ElSelect from "element-ui/packages/select/src/select";

// import ElSlider from "element-ui/packages/slider/src/main";

// import ElSlider from "element-ui/packages/slider/src/main";

// import ElTimeSelect from "element-ui/packages/date-picker/src/picker/time-select";

// import ElRate from "element-ui/packages/rate/src/main";

// import ElDatePicker from "element-ui/packages/date-picker/src/picker/date-picker";
// import ElTimePicker from "element-ui/packages/date-picker/src/picker/time-picker";

// import ElRadioGroup from "element-ui/packages/radio/src/radio-group";

export default {
  components: {
    // ElRadioGroup
    // ElTimePicker,
    // ElDatePicker
    // ElRate
    // ElTimeSelect
    // ElSlider
    // ElSlider
    // ElSelect
    // ElSelect
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
  data: function() {
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
    // return {
    //   select: '',
    //   state1: '',
    //   restaurants: []
    // }
    // return {
    //   num1: 2
    // }
    // return {
    //   items: [
    //     {
    //       value: 2,
    //       label: 2
    //     },
    //     {
    //       value: 3,
    //       label: 3
    //     }
    //   ],
    //   value1: [],
    //   value2: []
    // }
    // return {
    //   cities: [{
    //     value: 'Beijing',
    //     label: '北京'
    //   }, {
    //     value: 'Shanghai',
    //     label: '上海'
    //   }, {
    //     value: 'Nanjing',
    //     label: '南京'
    //   }, {
    //     value: 'Chengdu',
    //     label: '成都'
    //   }, {
    //     value: 'Shenzhen',
    //     label: '深圳'
    //   }, {
    //     value: 'Guangzhou',
    //     label: '广州'
    //   }],
    //   value: ''
    // }
    // return {
    //   options3: [{
    //     label: '热门城市',
    //     options: [{
    //       value: 'Shanghai',
    //       label: '上海'
    //     }, {
    //       value: 'Beijing',
    //       label: '北京'
    //     }]
    //   }, {
    //     label: '城市名',
    //     options: [{
    //       value: 'Chengdu',
    //       label: '成都'
    //     }, {
    //       value: 'Shenzhen',
    //       label: '深圳'
    //     }, {
    //       value: 'Guangzhou',
    //       label: '广州'
    //     }, {
    //       value: 'Dalian',
    //       label: '大连'
    //     }]
    //   }],
    //   value: []
    // }
    // return {
    //   options: [{
    //     value: 'zhinan',
    //     label: '指南',
    //     // disabled: true,
    //     children: [{
    //       value: 'shejiyuanze',
    //       label: '设计原则',
    //       children: [{
    //         value: 'yizhi',
    //         label: '一致'
    //       }, {
    //         value: 'fankui',
    //         label: '反馈'
    //       }]
    //     }]
    //   }],
    //   // selectedOptions: ['zhinan', 'shejiyuanze']
    //   selectedOptions: []
    // }
    // return {
    //   value: [new Date(2016, 9, 10, 8, 40), new Date(2016, 9, 10, 9, 40)],
    //   value: '',
    //   value: [],
    //   value1: '',
    //   options: {
    //     disabledDate(time) {
    //       return time.getTime() < Date.now()
    //     },
    //     shortcuts: [{
    //       text: '今天',
    //       onClick(picker) {
    //         picker.$emit('pick', new Date())
    //       }
    //     }, {
    //       text: '昨天',
    //       onClick(picker) {
    //         const date = new Date()
    //         date.setTime(date.getTime() - 360e0 * 1000 * 24)
    //         picker.$emit('picker', date)
    //       }
    //     }]
    //   }
    //   options: {
    //     shortcuts: [{
    //       text: '最近一周',
    //       onClick(picker) {
    //         const end = new Date()
    //         const start = new Date()
    //         start.setTime(start.getTime() - 3600 * 1000 * 24 * 7)
    //         picker.$emit('pick', [start, end])
    //       }
    //     }]
    //   }
    // return {
    //   fileList: [{name: 'food.jpeg', url: 'https://fuss10.elemecdn.com/3/63/4e7f3a15429bfda99bce42a18cdd1jpeg.jpeg?imageMogr2/thumbnail/360x360/format/webp/quality/100'}]
    // }
    // return {
    //   imageUrl: ''
    // }
    // return {
    //   value: 4.6
    // }
    // return {
    //   color: '#409EFF',
    //   color2: null,
    //   colors: [
    //     '#ff4500',
    //     '#ff8c00',
    //     '#ffd700',
    //     '#90ee90',
    //     '#00ced1',
    //     '#1e90ff'
    //   ]
    //
    // }
    // let gennerateData = function() {
    //   const data = []
    //   for (let i = 1; i <= 15; i++) {
    //     data.push({
    //       key: i,
    //       label: `备选项${i}`,
    //       disabled: i % 4 === 0
    //     })
    //   }
    //   return data
    // }
    // return {
    //   data: gennerateData(),
    //   value: [1, 4]
    // }
    // let gennerateData = () => {
    //   const data = []
    //   const cities = ['上海', '北京', '广州', '深圳', '成都']
    //   const pinyin = ['shanghai', 'beijing', 'guangzhou', 'shenzhen', 'chengdu']
    //   cities.forEach((city, index) => {
    //     data.push({
    //       label: city,
    //       key: index,
    //       pinyin: pinyin[index]
    //     })
    //   })
    //   return data
    // }
    // return {
    //   value: [],
    //   data: gennerateData(),
    //   renderFunc(h, option) {
    //     return (<span>{option.key} - {option.label}</span>)
    //   }
    // }
    // return {
    //   form: {
    //     name: '',
    //     region: '',
    //     date1: '',
    //     date2: '',
    //     delivery: false,
    //     type: [],
    //     resource: '',
    //     desc: ''
    //   }
    // }
    // return {
    //   ruleForm: {
    //     name: ''
    //   },
    //   rules: {
    //     name: [
    //       {required: true, message: '请选择活动名称', trigger: 'blur'},
    //       {min: 3, max: 5, message: '长度3-5字符', trigger: 'blur'}
    //     ]
    //   }
    // }
    // var checkAge = (rule, value, callback) => {
    //   if (!value) {
    //     return callback(new Error('年龄不能为空'))
    //   }
    //   setTimeout(() => {
    //     if (!Number.isInteger(value)) {
    //       callback(new Error('请输入数字'))
    //     } else {
    //       if (value < 18) {
    //         callback(new Error('必须年满18岁'))
    //       } else {
    //         callback()
    //       }
    //     }
    //   }, 1000)
    // }
    // var validatePass = (rule, value, callback) => {
    //   if (value === '') {
    //     callback(new Error('请输入密码'))
    //   } else {
    //     if (this.ruleForm.checkPass !== '') {
    //       this.$refs.ruleForm.validateField('checkPass')
    //     }
    //     callback()
    //   }
    // }
    // var validatePass2 = (rule, value, callback) => {
    //   if (value === '') {
    //     callback(new Error('请再次输入密码'))
    //   } else if (value !== this.ruleForm.pass) {
    //     callback(new Error('两次输入密码不一致！'))
    //   } else {
    //     callback()
    //   }
    // }
    // return {
    //   ruleForm: {
    //     pass: '',
    //     checkPass: '',
    //     age: ''
    //   },
    //   rules: {
    //     pass: [
    //       {validator: validatePass, trigger: 'blur'}
    //     ],
    //     checkPass: [
    //       {validator: validatePass2, trigger: 'blur'}
    //     ],
    //     age: [
    //       {validator: checkAge, trigger: 'blur'}
    //     ]
    //   }
    // }
    // return {
    //   forms: {
    //     domains: [{
    //       value: ''
    //     }],
    //     email: ''
    //   }
    // }
    return {
      tableData: [{
        date: '2016-05-02',
        name: '王小虎',
        address: '上海市普陀区金沙江路 1518 弄',
        tag: '公司'
      }, {
        date: '2016-05-04',
        name: '王小虎',
        address: '上海市普陀区金沙江路 1517 弄',
        tag: '家'
      }, {
        date: '2016-05-01',
        name: '王小虎',
        address: '上海市普陀区金沙江路 1519 弄',
        tag: '公司'
      }, {
        date: '2016-05-03',
        name: '王小虎',
        address: '上海市普陀区金沙江路 1516 弄',
        tag: '家'
      }]
    }
  },
  methods: {
    /*
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
    },
    querySearch (queryString, cb) {
      var rest = this.restaurants
      var result = queryString ? rest.filter(this.createFilter(queryString)) : rest
      cb(result)
    },
    querySearchAsyn (query, cb) {
      var rest = this.restaurants
      var result = query ? rest.filter(this.createFilter(query)) : rest
      clearTimeout(this.timeout)
      this.timeout = setTimeout(() => {
        cb(result)
      }, 3000 * Math.random())
    },
    createFilter (queryString) {
      return (restaurant) => {
        return (restaurant.value.toLocaleLowerCase().indexOf(queryString.toLowerCase())) === 0
      }
    },
    loadAll () {
      return [
        { 'value': '三全鲜食（北新泾店）', 'address': '长宁区新渔路144号' },
        { 'value': 'Hot honey 首尔炸鸡（仙霞路）', 'address': '上海市长宁区淞虹路661号' },
        { 'value': '新旺角茶餐厅', 'address': '上海市普陀区真北路988号创邑金沙谷6号楼113' },
        { 'value': '泷千家(天山西路店)', 'address': '天山西路438号' },
        { 'value': '胖仙女纸杯蛋糕（上海凌空店）', 'address': '上海市长宁区金钟路968号1幢18号楼一层商铺18-101' },
        { 'value': '贡茶', 'address': '上海市长宁区金钟路633号' },
        { 'value': '豪大大香鸡排超级奶爸', 'address': '上海市嘉定区曹安公路曹安路1685号' },
        { 'value': '茶芝兰（奶茶，手抓饼）', 'address': '上海市普陀区同普路1435号' },
        { 'value': '十二泷町', 'address': '上海市北翟路1444弄81号B幢-107' },
        { 'value': '星移浓缩咖啡', 'address': '上海市嘉定区新郁路817号' },
        { 'value': '阿姨奶茶/豪大大', 'address': '嘉定区曹安路1611号' },
        { 'value': '新麦甜四季甜品炸鸡', 'address': '嘉定区曹安公路2383弄55号' },
        { 'value': 'Monica摩托主题咖啡店', 'address': '嘉定区江桥镇曹安公路2409号1F，2383弄62号1F' },
        { 'value': '浮生若茶（凌空soho店）', 'address': '上海长宁区金钟路968号9号楼地下一层' },
        { 'value': 'NONO JUICE  鲜榨果汁', 'address': '上海市长宁区天山西路119号' },
        { 'value': 'CoCo都可(北新泾店）', 'address': '上海市长宁区仙霞西路' },
        { 'value': '快乐柠檬（神州智慧店）', 'address': '上海市长宁区天山西路567号1层R117号店铺' },
        { 'value': 'Merci Paul cafe', 'address': '上海市普陀区光复西路丹巴路28弄6号楼819' },
        { 'value': '猫山王（西郊百联店）', 'address': '上海市长宁区仙霞西路88号第一层G05-F01-1-306' },
        { 'value': '枪会山', 'address': '上海市普陀区棕榈路' },
        { 'value': '纵食', 'address': '元丰天山花园(东门) 双流路267号' },
        { 'value': '钱记', 'address': '上海市长宁区天山西路' },
        { 'value': '壹杯加', 'address': '上海市长宁区通协路' },
        { 'value': '唦哇嘀咖', 'address': '上海市长宁区新泾镇金钟路999号2幢（B幢）第01层第1-02A单元' },
        { 'value': '爱茜茜里(西郊百联)', 'address': '长宁区仙霞西路88号1305室' },
        { 'value': '爱茜茜里(近铁广场)', 'address': '上海市普陀区真北路818号近铁城市广场北区地下二楼N-B2-O2-C商铺' },
        { 'value': '鲜果榨汁（金沙江路和美广店）', 'address': '普陀区金沙江路2239号金沙和美广场B1-10-6' },
        { 'value': '开心丽果（缤谷店）', 'address': '上海市长宁区威宁路天山路341号' },
        { 'value': '超级鸡车（丰庄路店）', 'address': '上海市嘉定区丰庄路240号' },
        { 'value': '妙生活果园（北新泾店）', 'address': '长宁区新渔路144号' },
        { 'value': '香宜度麻辣香锅', 'address': '长宁区淞虹路148号' },
        { 'value': '凡仔汉堡（老真北路店）', 'address': '上海市普陀区老真北路160号' },
        { 'value': '港式小铺', 'address': '上海市长宁区金钟路968号15楼15-105室' },
        { 'value': '蜀香源麻辣香锅（剑河路店）', 'address': '剑河路443-1' },
        { 'value': '北京饺子馆', 'address': '长宁区北新泾街道天山西路490-1号' },
        { 'value': '饭典*新简餐（凌空SOHO店）', 'address': '上海市长宁区金钟路968号9号楼地下一层9-83室' },
        { 'value': '焦耳·川式快餐（金钟路店）', 'address': '上海市金钟路633号地下一层甲部' },
        { 'value': '动力鸡车', 'address': '长宁区仙霞西路299弄3号101B' },
        { 'value': '浏阳蒸菜', 'address': '天山西路430号' },
        { 'value': '四海游龙（天山西路店）', 'address': '上海市长宁区天山西路' },
        { 'value': '樱花食堂（凌空店）', 'address': '上海市长宁区金钟路968号15楼15-105室' },
        { 'value': '壹分米客家传统调制米粉(天山店)', 'address': '天山西路428号' },
        { 'value': '福荣祥烧腊（平溪路店）', 'address': '上海市长宁区协和路福泉路255弄57-73号' },
        { 'value': '速记黄焖鸡米饭', 'address': '上海市长宁区北新泾街道金钟路180号1层01号摊位' },
        { 'value': '红辣椒麻辣烫', 'address': '上海市长宁区天山西路492号' },
        { 'value': '(小杨生煎)西郊百联餐厅', 'address': '长宁区仙霞西路88号百联2楼' },
        { 'value': '阳阳麻辣烫', 'address': '天山西路389号' },
        { 'value': '南拳妈妈龙虾盖浇饭', 'address': '普陀区金沙江路1699号鑫乐惠美食广场A13' }
      ]
    },
    handleChange(value) {
      console.log(value)
    },
    change(value) {
      console.log(value)
    },
    formatTooltip(value) {
      return value / 100.0
    }

    handleExceed(files, fileList) {
      this.$message.warning(`当前限制选择3个文件，本次选了${files.length}, 一共选择了${files.length + fileList.length}个文件`)
    },
    beforeRemove(file, fileList) {
      return this.$confirm(`确定要溢出${file.name}?`)
    },
    filterMethod(query, item) {
      return item.pinyin.indexOf(query) > -1
    }
  */
    addDomain() {
      this.forms.domains.push({
        value: '',
        key: Date.now()
      })
    }
  }
  // mounted () {
  //   this.restaurants = this.loadAll()
  // }
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
  /*.el-select {*/
    /*width: 130px;*/
  /*}*/
  /*.my-autocomplete {*/
    /*li {*/
      /*line-height: normal;*/
      /*padding: 7px;*/
      /*.name {*/
        /*text-overflow: ellipsis;*/
        /*overflow: hidden;*/
      /*}*/
      /*.addr {*/
        /*font-size: 12px;*/
        /*color: #b4b4b4;*/
      /*}*/
    /*}*/
  /*}*/
  .avatar-uploader .el-upload {
    border: 1px dashed #d9d9d9;
    border-radius: 6px;
    cursor: pointer;
    position: relative;
    overflow: hidden;
  }
  .avatar-uploader .el-upload:hover {
    border-color: #409EFF;
  }
  .avatar-uploader-icon {
    font-size: 28px;
    color: #8c939d;
    width: 178px;
    height: 178px;
    line-height: 178px;
    text-align: center;
  }
  .avatar {
    width: 178px;
    height: 178px;
    display: block;
  }
</style>
