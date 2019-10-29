<template>
  <div class="binary-tree">{{tree}}</div>
</template>

<script>

export default {
  name: 'binary-tree',
  props: {
    tree: Array
  },
  data: () => {
    return {}
  },
  methods: {}
}
</script>

<style>
  .binary-tree {
    font-size: 12px;
  }
</style>
