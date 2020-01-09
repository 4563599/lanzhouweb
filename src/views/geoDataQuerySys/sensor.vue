<template>
  <div>
    <img src="@/assets/img/sensor.png" alt="">
    <panel-group :dialogStatus.sync="dialog" />
  </div>
</template>

<script>
  import PanelGroup from "./components/PanelGroup";
  export default {
    components: {
      PanelGroup,
    },
    data() {
      return {
        dialog: false
      }
    },
  }
</script>

<style lang="scss" scoped>

</style>