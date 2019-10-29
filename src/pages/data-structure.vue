<template>
  <div class="data-structure">
    <div class="menu-type">
      <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal">
        <!-- <el-menu-item index="1">数据结构</el-menu-item> -->
        <el-menu-item index="2">算法</el-menu-item>
      </el-menu>
    </div>
    <binary-tree :tree="tree"></binary-tree>
  </div>
</template>

<script>
import BinaryTree from '../components/common/binary-tree.vue'

export default {
  name: 'data-structure',
  components: { BinaryTree },
  mounted () {
    this.init();
  },
  data: () => {
    return {
      activeIndex: '2',
      tree: {}
    }
  },
  methods: {
    init () {
      this.tree = {
        value: 1,
        left: {
          value: 2,
          left: null,
          right: null
        },
        right: {
          value: 3,
          left: null,
          right: null
        }
      }
    }
  }
}
</script>

<style>
  .data-structure {
    font-size: 12px;
  }
</style>
