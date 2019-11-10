<template>
    <nav>
        <box-icon name='home'></box-icon>
        <box-icon name='trophy'></box-icon>
        <box-icon name='list-ul'></box-icon>
        <box-icon name='user-detail' type='solid'></box-icon>
        <box-icon name='bar-chart-square'></box-icon>
        <box-icon name='wrench'></box-icon>
    </nav>
</template>

<script>
import 'boxicons'
export default {
    data() {
        return {
            user: "Chewy",
            userCash: "49.63"
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";

    nav {
        text-align: center;
        background: $light;
    }
    box-icon {
        margin: 1em;
    }
</style>