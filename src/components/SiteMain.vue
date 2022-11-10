<script>

export default {
    name: `SiteMain`
}

</script>


<template>

    <main id="site-main">
        <section class="content">
            <div class="container">
                <div class="box">
                    <h3>- - > Content goes here - -</h3>
                </div>
                <!-- /.box -->
            </div>
        </section>
        <!-- /.container -->
        <section class="info">
            <div class="container">
                <div class="nav">
                    <div class="square">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <h5>Digital Comics</h5>
                    </div>
                    <div class="square">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <h5>Dc Merchandise</h5>
                    </div>
                    <div class="square">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <h5>Subscription</h5>
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
        <!-- /.container -->
    </main>

</template>

<style lang="scss" scoped>
.content {
    background-color: #1C1C1C;

    .container {
        width: 80%;
        margin: auto;
        padding: 2rem;
        display: flex;
        justify-content: space-between;


        h3 {
            color: white;
        }
    }

}


.info {
    background-color: #0282F9;

    .container {
        width: 80%;
        margin: auto;
        padding: 2rem;
        position: relative;
        z-index: 1;

        .nav {
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