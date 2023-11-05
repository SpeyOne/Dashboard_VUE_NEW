<template>
<div class="collums_charts">
    <three-row-chart></three-row-chart>
    <line-column-chart></line-column-chart>
</div>
</template>

<script>
import ThreeRowChart from './ThreeRowChart.vue'
import LineColumnChart from './LineColumnChart.vue'
export default {
    name: 'App',
    components:
    { ThreeRowChart,
        LineColumnChart

}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

.collums_charts {
    display: flex;
    flex-direction: row;
    max-width: 100%;
    height: 480px;
    margin-left: 300px;
    margin-right: 80px;
}

</style>