<template lang="pug">
.con
  el-button(type="warning")
    |click me
</template>
<script>
import _ from 'lodash'
export default {
  name: "orders",
  data(){
    return {
      da: 'vddd'
    }
  },
  created() {
    const a = [4, 65, 90]
    const b= _.indexOf(a, 65)
    console.log(b, 2)
  }
}
</script>

<style scoped lang="stylus">
.con
  width: 100px
  height: 200px
  border: 1px blue solid
</style>