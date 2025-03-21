<template lang="html">
  <header class="header">
    <h1>The Magnificent Seven Companies</h1>
  </header>
</template>

<script lang="js">

export default {
  name: 'AppHeader',
  props: [],
  mounted() {},
  data() {
    return {}
  },
  methods: {},
  computed: {}
}
</script>

<style scoped lang="scss">
.header {
  display: flex;
  padding: 30px;

  > h1 {
    color: #F9F9F9;
    margin-left: 60px;
    position: relative;

    &::before {
      content: "";
      position: absolute;
      transform: translateY(-50%);
      top: 50%;
      left: -90px;
      width: 70px;
      height: 20px;
      border-radius: 0 30px 30px 0;
      background-color: #39DAFF;
    }
  }
}
</style>
