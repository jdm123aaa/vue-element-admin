<template>
  <div class="components-container" style='height:100vh'>
    https://github.com/ecomfe/echarts/blob/master/index.js
    http://echarts.baidu.com/tutorial.html
    <div class='chart-container'>
       <lineMarker height='100%' width='100%' />
    </div>

  </div>
</template>
<script>
    import lineMarker from 'components/Charts/lineMarker';

    export default {
      components: { lineMarker }
    };
</script>

<style scoped>
.chart-container{
    position: relative;
    width: 100%;
    height: 80%;
}
</style>

