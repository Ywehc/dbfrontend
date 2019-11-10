<template>
    <section class="scores">
        <div class="boxscore">
            <div class="away-team">
                <div class="away-team-logo">
                    <img class="team-logo" src="../assets/images/redwings.gif">
        
                </div>
                <div class="away-team-score redwings">
                    <p class="score">4</p>
                </div>
            </div>
            <div class="home-team">
                <div class="home-team-logo">
                    <img class="team-logo" src="../assets/images/leafs.png">
                </div>
                <div class="home-team-score leafs">
                    <p class="score">3</p>
                </div>
        
            </div>         
        </div>
        <div class="boxscore">
            <div class="away-team">
                <div class="away-team-logo">
                    <img class="team-logo" src="../assets/images/oilers.gif">
        
                </div>
                <div class="away-team-score oilers">
                    <p class="score">2</p>
                </div>
            </div>
            <div class="home-team">
                <div class="home-team-logo">
                    <img class="team-logo" src="../assets/images/hawks.gif">
                </div>
                <div class="home-team-score hawks">
                    <p class="score">5</p>
                </div>
        
            </div>
        
        </div>
        <div class="boxscore">
            <div class="away-team">
                <div class="away-team-logo">
                    <img class="team-logo" src="../assets/images/wild.gif">
        
                </div>
                <div class="away-team-score wild">
                    <p class="score">6</p>
                </div>
            </div>
            <div class="home-team">
                <div class="home-team-logo">
                    <img class="team-logo" src="../assets/images/senators.gif">
                </div>
                <div class="home-team-score sens">
                    <p class="score">0</p>
                </div>
        
            </div>
        
        </div>
        <div class="boxscore">
            <div class="away-team">
                <div class="away-team-logo">
                    <img class="team-logo" src="../assets/images/canadiens.gif">
        
                </div>
                <div class="away-team-score habs">
                    <p class="score">1</p>
                </div>
            </div>
            <div class="home-team">
                <div class="home-team-logo">
                    <img class="team-logo" src="../assets/images/sharks.gif">
                </div>
                <div class="home-team-score sharks">
                    <p class="score">2</p>
                </div>
        
            </div>
        
        </div>
    </section>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
    @import "./scss/variables.scss";
    .scores {
        display: flex;
        background: $dark;
    }
    .boxscore {
        background: white;
        width: 70px;
        height: 70px;
        margin: .5em auto;
        border: 2px solid $light;
    }
    .away-team, .home-team {
        height: 49%;
        width: 100%;
        font-family: 'Righteous', cursive;
    }
    .away-team {
        display: flex;
    }
    .away-team-logo, .away-team-score, .home-team-logo, .home-team-score {
        height: 100%;
        width: 50%;
    }
    .home-team {
        display: flex;
        border-top: 2px solid $light;
    }
    .away-team-logo, .home-team-logo, .away-team-score, .home-team-score {
        display: flex;
        justify-content: center; /* align horizontal */
        align-items: center; /* align vertical */
    }
    .team-logo {
        width: 1.5em;
    }
    .redwings {
        background: #cc0a34;
        color: white;
    }
    .leafs {
        background: #002663;
        color: white;
    }
    .oilers {
        background: #00285a;
        color: white;
    }
    .hawks {
        background: #e73439;
        color: white;
    }
    .wild {
        background: #005931;
        color: white;
    }
    .sens {
        background: #d69f0f;
        color: white;
    }
    .habs {
        background: #bd2c39;
        color: white;
    }
    .sharks {
        background: #215d6b;
        color: white;
    }
</style>