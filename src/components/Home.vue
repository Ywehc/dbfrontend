<template>
     <div>
        <Feed />
        <UserOverview />
     </div>
</template>

<script>
import Feed from './Feed.vue'
import UserOverview from './UserOverview.vue'
export default {
    components: {
    Feed,
    UserOverview
  }    
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
</style>