<template>
    <div>
        <img alt="stick and puck logo" src="@/assets/images/stick_puck.png">
        <h1>
            <span class="heading-draft">DRAFT</span>
            <span class="heading-boom">BOOM</span>
        </h1>
    </div>  
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";

    header {
        background: $light;
        height: 100px;
    }
    h1 {
        font-family: $font-logo;
    }
    .heading-draft {
        color: $darker;
    }
    .heading-boom {
        color: $dark;
    }
</style>