<template>
     <section>
        <ul class="updates-list">
            <li>Semyon Varlamov will be in goal Sunday</li>
            <li>Ondrej Kase looks close to return</li>
            <li>Alex Goligoski (LBI) won't play on Sunday</li>
            <li>Richard Panik draws back in Sunday</li>
            <li>Darcy Kuemper to start again on Sunday</li>
            <li>Braden Holtby will get the call on Sunday</li>
            <li>Backstrom to play with Ovechkin on Sunday</li>
            <li>John Carlson (LBI) will be a game-time call</li>
            <li>Brayden Schenn (UBI) set to sit on Sunday</li>
            <li>Alexander Radulov slated to return Monday</li>
            <li>Marc Methot 3-5 days from skating again</li>
            <li>Tom Wilson's suspension reduced to 14 games</li>
            <li>Connor Carrick out for another two weeks</li>
            <li>Devin Shore (LBI) set to miss 7-10 days</li>
            <li>Alex DeBrincat scores in OTL to Hurricanes</li>
            <li>Auston Matthews will travel with teammates</li>
        </ul>
     </section>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
    section {
        background: $darker;
        color: $light;
        padding: 1.5em;
        height: 30vh;
        overflow: hidden;
        overflow-y: scroll;
        font-family: $font-feed;
    }
    ul {
        list-style-type: none;
        padding: 0;
        border: 2px solid $lighter;
        border-radius: 2%;        
    }
    li {
        margin: .2em;
        padding: .2em;
    }
    li:nth-child(odd) { background: $dark; }

</style>