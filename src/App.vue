<template>
  <div id="app">
    <PageHeader/>
    <DashBoard/>
    <WavyChart/>
    <CrunchBoard/>
    <CollumsChartsContainer/>
    <ProgressBoard/>
    <ProgressBars/>
    <CrunchBoard/>
    <BottomChartsContainer/>
    <NavBarVF/>
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue'
import NavBarVF from './components/NavBarVF.vue'
import DashBoard from './components/DashBoard.vue'
import WavyChart from './components/WavyChart.vue'
import CrunchBoard from './components/CrunchBoard.vue'
import CollumsChartsContainer from './components/CollumsChartsContainer.vue'
import ProgressBoard from './components/ProgressBoard.vue'
import ProgressBars from './components/ProgressBars.vue'
import BottomChartsContainer from './components/BottomChartsContainer.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    NavBarVF,
    DashBoard,
    WavyChart,
    CrunchBoard,
    CollumsChartsContainer,
    ProgressBoard,
    ProgressBars,
    BottomChartsContainer
  }
}
</script>

<style>
#app {
  min-width: auto;
  font-family: "Myriad Pro", 'Myriad', "Liberation Sans", "Nimbus Sans L", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 16px;
  line-height: 24px;
  color: #404040;
  background-color: #f5f5f5;
}


</style>
