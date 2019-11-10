<template>
     <div>
        <Feed />
        <Dashboard />
        <Players />
        <BoxScores />
     </div>
</template>

<script>
import Feed from './Feed.vue'
import Dashboard from './Dashboard.vue'
import Players from './Players.vue'
import BoxScores from './BoxScores.vue'

export default {
    components: {
    Feed,
    Dashboard,
    BoxScores,
    Players
  }    
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
</style>