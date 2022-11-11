<script>
export default {
    name: `SectionBanner`
}
</script>


<template>
    <section class="banner">
        <div class="container">
            <div class="info">
                <div class="square">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <h5>Digital Comics</h5>
                </div>
                <div class="square">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <h5>Dc Merchandise</h5>
                </div>
                <div class="square">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt=""> // Rendere dinamche le immagine
                    attraverso un ciclo for //
                    <h5>Subscription</h5> // Ceare un components Banner così da separare il tutto //
                </div>
                <div class="square">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <h5>Comic Shop Locator</h5>
                </div>
                <div class="square">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <h5>Dc Power Visa</h5>
                </div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
.banner {
    background-color: #0282F9;

    .container {
        width: 80%;
        margin: auto;
        padding: 2rem;
        position: relative;
        z-index: 1;

        .info {
            display: flex;

            .square {
                display: flex;
                align-items: center;
                margin: 0 1rem;
                color: white;
                text-transform: uppercase;

                img {
                    width: 20%;
                    margin-right: 1rem;
                }
            }


        }

    }

}
</style>