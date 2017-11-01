<template>
    <button class="sn-btn"
      type="button"
      value="点击我"
      :class="[
        type ? 'sn-btn--' + type : ''
      ]"
    >sdsdsd</button>
</template>

<script>
  export default {
    name: 'app',
    props: {
      type: {
        type: String,
        default: 'primary'
      }
    },
    methods: {
    }
  };
</script>
