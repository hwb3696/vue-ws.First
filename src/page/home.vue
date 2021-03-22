<template>
  <div>
    <head-top></head-top>
    <section class="data_section"></section>
    <tendency :sevenDate="sevenDate" :sevenDay="sevenDay"></tendency>
  </div>
</template>

<script>
import headTop from "../components/headTop";
import tendency from "../components/tendency";
import dtime from "time-formater";
// import {userCount, orderCount, getUserCount, getOrderCount, adminDayCount, adminCount} from '@/api/getData'
export default {
  data() {
    return {};
  },
  components: {
    headTop,
    tendency,
  },
  mounted() {},
  computed: {},
  methods: {},
};
</script>

<style lang="less">
@import "../style/mixin";
.data_section {
}
.wan {
  .sc(16px, #333);
}
</style>
