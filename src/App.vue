<template lang="pug">
.content
  od
  .names
    |321
</template>

<script>
import _ from 'lodash'
import od from '@/pages/orders'
export default {
  name: "App.vue",
  components: {
    od
  },
  data() {
    return {
      fd: "bbb"
    }
  },
  created() {

  }
}
</script>

<style scoped lang="stylus">
.content
  border: 1px red solid
</style>