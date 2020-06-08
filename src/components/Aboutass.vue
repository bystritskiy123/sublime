<template>
    <div id="Aboutass">
        <div class="row col-md-12">
            <div class="col-md-5" id="part_1">
                <h3>About</h3>
                <h4><span>S</span>ublime</h4>
            </div>
            <div class="col-md-7" id="part_2">
                <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisis molestie dignissim. Nulla
                    pellentesque et nisi et euismod. Pellentesque quis tristique magna.</h3>

                <h4>Maecenas est risus, tristique volutpat sagittis vel, feugiat consectetur diam. Suspendisse justo
                    sem,
                    molestie tincidunt rhoncus vel, molestie ut ligula. Mauris vitae ullamcorper odio. Mauris id enim
                    gravida, tempor velit non, vehicula lacus. Sed rutrum tempus urna, sed aliquam lectus egestas eu.
                    Maecenas est risus, tristique volutpat sagittis vel, feugiat consectetur diam. Suspendisse justo
                    sem,
                    molestie tincidunt rhoncus vel, molestie ut ligula. Mauris vitae ullamcorper odio. Mauris id enim
                    gravida, tempor velit non, vehicula lacus. Sed rutrum tempus urna, sed aliquam lectus egestas eu
                </h4>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Aboutass',
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

    @font-face {
        font-family: 'MyriadProItalic';
        src: url('../fonts/MyriadProItalic.ttf') format("truetype");
    }

    #Aboutass {
        .row {
            #part_1 {
                h3 {
                    margin-left: 20%;
                    margin-top: 30%;
                    font-family: 'MyriadProRegular';
                    font-size: 400%;
                    color: gray;
                }

                h4 {
                    margin-left: 20%;
                    font-family: 'MyriadProRegular';
                    font-size: 600%;

                    span {
                        color: yellow;
                    }
                }
            }


            #part_2 {
                h3 {
                    margin-top: 15%;
                    font-size: 110%;
                    font-family: 'MyriadProItalic';
                }

                h4 {
                    margin-top: 10%;
                    font-size: 110%;
                    font-family: 'MyriadProItalic';
                }

            }
        }
    }
</style>