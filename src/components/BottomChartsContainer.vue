<template>
<div class="bottom_charts">
    <pie-chart></pie-chart>
    <general-menu></general-menu>
    <total-overdue></total-overdue>
</div>
</template>

<script>
import PieChart from './PieChart.vue'
import GeneralMenu from './GeneralMenu.vue'
import TotalOverdue from './TotalOverdue.vue'
export default {
    name: 'App',
    components:
    { PieChart, 
        GeneralMenu, 
        TotalOverdue 
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

.bottom_charts {
    display: flex;
    flex-direction: row;
    justify-content: center;
    max-width: 100%;
    height: 500px;
    margin-left: 300px;
    margin-right: 80px;
    padding-bottom: 50px;
}

</style>