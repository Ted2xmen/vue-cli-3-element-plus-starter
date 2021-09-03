<template>
  <div class="container">
    <el-row justify="center p-20">
      <img
        width="500"
        src="https://user-images.githubusercontent.com/10731096/95823103-9ce15780-0d5f-11eb-8010-1bd1b5910d4f.png"
        alt=""
    /></el-row>
    <el-row class="row-bg p-20" justify="center ">
      <el-badge :value="2" class="item" type="warning">
        <el-button size="small">replies</el-button>
      </el-badge>
      <el-col :span="3"
        ><div class="grid-content bg-purple">
          <el-button type="primary">Primary</el-button>
        </div></el-col
      >
      <el-col :span="3"
        ><div class="grid-content bg-purple">
          <el-link href="https://element-plus.org/#/en-US" target="_blank"
            >Element Plus</el-link
          >
        </div></el-col
      >
      <el-col :span="3"
        ><div class="grid-content bg-purple">
          <el-button type="success">Success</el-button>
        </div></el-col
      >
      <el-rate v-model="value1"></el-rate>
    </el-row>
    <el-row class="row-bg p-20" justify="center">
      <ul>
        <h3 class="p-5">Installed CLI Plugins</h3>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
            target="_blank"
            rel="noopener"
            >babel</a
          >
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router"
            target="_blank"
            rel="noopener"
            >router</a
          >
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex"
            target="_blank"
            rel="noopener"
            >vuex</a
          >
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint"
            target="_blank"
            rel="noopener"
            >eslint</a
          >
        </li>
      </ul>
    </el-row>
  </div>
</template>

<style scoped>
.p-20 {
  padding: 20px;
}
.p-5 {
  padding: 5px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>