<template>
  <div id="cesiumContainer" />
</template>

<script>
import Cesium from 'cesium/Cesium';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  mounted() {
    new Cesium.Viewer('cesiumContainer');
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
