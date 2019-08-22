<template>
  <div id="app">
    <search-input placeholder="请输入可搜索列名称"
                  size="mini"
                  :data="searchData"
                  :prop="defaultProp"></search-input>
  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
      searchData: [
        {
          id: 1,
          label: "展示数"
        }, {
          id: 2,
          label: "点击数"
        }, {
          id: 3,
          label: "点击成本点击"
        }, {
          id: 4,
          label: "点xx击"
        }
      ],
      defaultProp: {
        label: "label"
      },
    }
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
