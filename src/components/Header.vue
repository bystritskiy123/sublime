<template>
    <div id="header">
        <h4><span>S</span>ublime</h4>
        <h5>Sublime: A one page responsive wordpress theme
            suitable for any kind of business representation.</h5>
        <h6><a href="#">download the psd</a></h6>
        <div id="menu" class="container-fluid">
            <h4><span>W</span>ecreate</h4>
            <h5>Awesome games</h5>
            <nav>
                <ul class="row">
                    <li><a href="#">About</a></li>
                    <li><a href="#">Development</a></li>
                    <li><a href="#">Projects</a></li>
                    <li><a href="#">Blog</a></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Header',
        data() {
            return {

            }
        }

    }
</script>

<style lang="scss" scoped>
    @font-face {
        font-family: 'MyriadProBold';
        src: url('../fonts/MyriadProBold.ttf') format("truetype");
    }

    @font-face {
        font-family: 'MyriadProRegular';
        src: url('../fonts/MyriadProRegular.ttf') format("truetype");
    }

    #header {
        background-image: url('../assets/header.png');
        background-size: cover;
        width: 100%;
        height: 100%;
        display: inline-block;

        h4 {
            color: white;
            font-family: "MyriadProBold";
            font-size: 1300%;
            margin-top: 3%;
            margin-left: 10%;

            span {
                color: yellow;
            }
        }

        h5 {
            width: 30%;
            color: white;
            font-family: 'MyriadProRegular';
            margin-left: 11%;
        }

        h6 {
            margin-left: 11%;
            margin-top: 3%;
            font-family: "MyriadProRegular";

            a {
                color: yellow;
                text-decoration: none;
            }
        }

        #menu {
            background-image: url('../assets/menu.png');
            background-size: cover;
            width: 90%;
            height: 45rem;
            margin-top: 10%;
            margin-left: 5%;
            display: inline-block;

            h4 {
                font-size: 500%;
                margin-left: 5%;
                margin-top: 4%;
                font-family: "MyriadProBold";
            }

            h5 {
                width: 100%;
                margin-left: 5%;
                font-family: "MyriadProBold";
                font-size: 300%;
            }

            nav {
                ul {
                    margin-top: 4%;

                    li {
                        list-style-type: none;
                        margin-left: 3%;
                        font-family: "MyriadProRegular";
                        font-size: 110%;

                        a {
                            color: yellow;
                            text-decoration: none;
                        }
                    }
                }
            }
        }
    }
</style>