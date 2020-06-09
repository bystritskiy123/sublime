<template>
    <div id="card">
        <div class="card-group">
            <div class="card">
                <img src="../assets/game.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h3 align="center">app development</h3>
                    <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisis
                        molestie dignissim. Nulla pellentesque et nisi et euismod. Pellentesque quis tristique magna.
                    </p>

                    <p class="card-text">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisis molestie dignissim.
                        Nulla
                        pellentesque et nisi et euismod. Pellentesque quis tristique magna.
                    </p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/game.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h3 align="center">game dasing</h3>
                    <p class="card-text">Lorem ipsum dolor sit amet, consectetur
                        adipiscing elit. Nulla facilisis
                        molestie dignissim. Nulla pellentesque et nisi et euismod. Pellentesque quis tristique magna.
                    </p>

                    <p class="card-text">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisis molestie dignissim.
                        Nulla
                        pellentesque et nisi et euismod. Pellentesque quis tristique magna.
                    </p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/game.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h3 align="center">content creation</h3>
                    <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisis
                        molestie dignissim. Nulla pellentesque et nisi et euismod. Pellentesque quis tristique magna.
                    </p>

                    <p class="card-text">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisis molestie dignissim.
                        Nulla
                        pellentesque et nisi et euismod. Pellentesque quis tristique magna.
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Card',
        data() {
            return {

            }
        }
    }
</script>

<style lang="scss" scoped>
    @font-face {
        font-family: 'MyriadProRegular';
        src: url('../fonts/MyriadProRegular.ttf') format("truetype");
    }

    #card {
        margin-top: 15%;
    }

    .card {
        border: 0px;
        font-family: 'MyriadProRegular';
    }

    .card-img-top {
        width: 20%;
        margin-left: 40%;
    }
</style>