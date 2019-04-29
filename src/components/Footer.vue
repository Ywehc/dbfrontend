<template>
    <footer>
        <p>{{copyright}}</p>
    </footer>    
</template>

<script>
export default {
    data() {
        return {
            copyright: "Copyright 2019 CK"
        }
    }
    
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
    footer {
    background: $dark;
    height: 100px;
    }
</style>