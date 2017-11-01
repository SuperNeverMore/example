<template>
  <div class="demo">
      <Demo></Demo>
      <i class="icon iconfont icon-check"></i>
      <Demo type="success"></Demo>
      <Demo type="info"></Demo>
      <Demo type="warning"></Demo>
      <Demo type="danger"></Demo>
  </div>
</template>

<script>
  import Demo from '../src/sn-btn/sn-btn';
  export default {
    name: 'app',
    components: {
      Demo
    }
  };
</script>
<style lang="less">
    @import url(../static/styles/sn-btn.less);
    .demo {
        margin: 30px auto 0;
        width: 500px;
    }
</style>