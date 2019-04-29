<template>
    <header>
        <h1>{{title}}</h1>
    </header>    
</template>

<script>
export default {
    data() {
        return {
            title: 'Header'
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
    header {
    background: $dark;
    height: 100px;
    }
</style>



