<script>
export default {

}
</script>

<template>
    <footer>
        <div class="foot-container">
            <div class="foot-top">
                <div class="logo-bg">
                    <!-- img in bg -->
                    <div class="left">
                        <div>
                            <!-- col.1 -->
                            <ul>
                                <h2>DC COMICS</h2>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                            </ul>
                        </div>

                        <!-- col.2 -->
                        <div>
                            <ul>
                                <h2>DC</h2>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                            </ul>
                        </div>

                        <!-- col.3 -->
                        <div>
                            <ul>
                                <h2>SITE</h2>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                                <li><a href="#">link</a></li>
                            </ul>

                        </div>
                    </div>
                    <div class="right">
                        <!-- logo DC -->
                        <img src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>


            </div>
            <div class="foot-bottom">
                <button>SIGN-IP NOW!</button>

                <ul class="social">
                    <h2>
                        FOLLOW US
                    </h2>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-pinterest.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </a>
                    </li>
                </ul>
            </div>


        </div>
    </footer>
</template>
<style lang="scss" scoped>
@use "../scss/mixin.scss" as *;


.logo-bg {
    display: flex;
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 300px;
}

h2 {
    color: #fff;
}

.left,
.right {
    width: 50%;
    display: flex;
    justify-content: center;

    ul {
        display: flex;
        flex-direction: column;
        padding-top: 30px;

        a {
            color: rgb(122, 122, 122);
        }
    }
}

.left>div {
    width: calc(100% / 3 - 40px);
    padding: 0 20px;
}

.foot-bottom {
    background-color: lightslategrey;
    display: flex;
    justify-content: space-between;

    h2 {
        color: blue;
        padding-right: 10px;
    }

    button {
        margin-left: 60px;
    }

    ul {
        display: flex;
        margin: 20px;

        li {
            display: inline-block;
        }
    }
}
</style>