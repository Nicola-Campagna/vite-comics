<script>
export default {

}
</script>

<template>
    <main>
        <div class="option-container">

            <ul>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="icon">
                        <h3>DIGITAL COMICS</h3>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="icon">
                        <h3>DC MERCHANDASING</h3>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="icon">
                        <h3>SUBSCRITION</h3>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="icon">
                        <h3>SHOP</h3>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="icon">
                        <h3>DC POWER VISA</h3>
                    </a>
                </li>
            </ul>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use "../scss/mixin.scss" as *;

.option-container {
    @include flex-center();
    background-color: blue;
    height: 200px;
}

img {
    height: 50px;
    text-align: center;
    display: flex;
}

h3 {
    font-size: 10px;
    padding-left: 5px;
}

ul li {
    padding: 0 10px
}

a {
    @include flex-center();
    color: #fff;
}
</style>