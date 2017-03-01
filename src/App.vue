<template>
  <div id="app">
    <div class="container">
      <div class="Chart__list">
        <div class="Chart">
          <h2>Linechart 1</h2>
          <line-chart></line-chart>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="Chart__list">
        <div class="Chart">
          <h2>Linechart 2</h2>
          <line-chart></line-chart>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="Chart__list">
        <div class="Chart">
          <h2>Linechart 3</h2>
          <line-chart></line-chart>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="Chart__list">
        <div class="Chart">
          <h2>Linechart 4</h2>
          <line-chart></line-chart>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import LineChart from './components/LineChart.js'
export default {
  name: 'app',
  components: {
    LineChart
  }
}
</script>
