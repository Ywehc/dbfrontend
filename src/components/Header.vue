<template>
    <header>
        <div class="logo-container">
            <img src="../assets/images/stick_puck.png" alt="logo image">
        </div>
        <h1>Draft<span class="highlight">BOOM</span></h1>
    </header>    
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
    header {
        background: $lighter;
        height: 100px;
        display: flex;
        font-family: $font-logo;
    }
    .logo-container img {
        width: 60px;
        margin: 10px;
    }
    h1 {
        color: $darker;
    }
    .highlight {
        color: $dark;
    }
</style>



