<template>
     <div>
        <Feed />
        <Dashboard />
        <BoxScores />
     </div>
</template>

<script>
import Feed from './Feed.vue'
import Dashboard from './Dashboard.vue'
import BoxScores from './BoxScores.vue'

export default {
    components: {
    Feed,
    Dashboard,
    BoxScores
  }    
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
</style>