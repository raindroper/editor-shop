<template>
  <div class="main">
  <el-container>
    <el-aside width="200px">
      <util></util>
    </el-aside>
    <el-main>
      <show></show>
      <div class="aside-right">
        <edit></edit>
      </div>
    </el-main>
  </el-container>
  </div>
</template>

<script>
import edit from '@/components/edit'
import util from '@/components/util'
import show from '@/components/show'
export default {
  components: {
    edit,
    util,
    show
  },
  data () {
    return {}
  }
}
</script>

<style>

</style>
