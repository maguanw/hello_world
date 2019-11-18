<template>
  <div class="swip">
    <div class="test">
      <mt-swipe :auto="1000">
        <mt-swipe-item>1</mt-swipe-item>
        <mt-swipe-item>2</mt-swipe-item>
        <mt-swipe-item>3</mt-swipe-item>
      </mt-swipe>
    </div>
  </div>
</template>

<script>

export default {
  name: 'swip',
  mounted () {
    this.init();
  },
  data: () => {
    return {
    }
  },
  methods: {
    init () {

    }
  }
}
</script>

<style>
  .swip {
    font-size: 12px;
  }
  .test {
    height: 200px;
  }
</style>
