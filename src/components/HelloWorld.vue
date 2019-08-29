<template>
  <!--<el-form>-->
  <el-from-item label="Cron">
    <span></span>
    <input-cron v-model="cycleExpr" :hide-year="true"></input-cron>
  </el-from-item>
  <!--</el-form>-->
</template>

<script>
  import InputCron from './common/input-cron'

  export default {
    components: {
      InputCron

    },

    name: 'HelloWorld',
    data() {
      return {
        // cycleExpr: '1-3 1-2/2 0-3/2,3 7-8/3 1-2/1 ?',
        cycleExpr: '0 0 0-3/2,3 7-8/3 1-2/1 ?',
        // cycleExpr: '0,4 0,4 0,2,3 7-8 1 ?',
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
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
