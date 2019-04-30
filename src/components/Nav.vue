<template>
    <nav>
        <ul>
            <li>Home</li>
            <li>Rankings</li>
            <li>Roster</li>
            <li>Players</li>
            <li>Analytics</li>
            <li>Settings</li>
        </ul>
    </nav>
</template>

<script>
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
        font-family: $font-logo;
        margin: auto;
    }
    nav ul {
        list-style-type: none;
        display: flex;
        padding: 0;
    }
</style>