<script>

export default {
    name: `SiteFooter`
}

</script>


<template>

    <footer id="site-footer">
        <section class="list">
            <div class="container">
                <div class="left">
                    <div class="box">
                        <h3>Dc Comics</h3>
                        <p>Characters</p>
                        <p>Comics</p>
                        <p>Movies</p>
                        <p>Tv</p>
                        <p>Games</p>
                        <p>Videos</p>
                        <p>News</p>
                        <h3>Shop</h3>
                        <p>Shop Dc</p>
                        <p>Shop Dc Collections</p>
                    </div>
                    <div class="box">
                        <h3>Dc</h3>
                        <p>Characters</p>
                        <p>Comics</p>
                        <p>Movies</p>
                        <p>Tv</p>
                        <p>Games</p>
                        <p>Videos</p>
                        <p>News</p>
                        <p>Shop Dc</p>
                        <p>Shop Dc Collectibles</p>
                        <p>Shop Dc</p>
                        <p>Shop Dc Collectibles</p>
                    </div>
                    <div class="box">
                        <h3>Sites</h3>
                        <p>Characters</p>
                        <p>Comics</p>
                        <p>Movies</p>
                        <p>Tv</p>
                        <p>Games</p>
                    </div>
                </div>
                <!-- /.left -->
                <div class="rigth">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
                <!-- /.rigth -->
            </div>
            <!-- /.container -->
        </section>

        <section class="contact">
            <div class="container">
                <a href="#">Sign-Up-Now</a>
                <div class="social">
                    <h3>Follow Us</h3>

                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">

                </div>
                <!-- /.social -->
            </div>
            <!-- /.container -->
        </section>
    </footer>

</template>

<style lang="scss" scoped>
.list {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;

    .container {
        width: 80%;
        margin: auto;
        padding: 2rem;
        display: flex;
        justify-content: space-between;

        img {
            position: absolute;
            right: 170px;
            top: 200px;
        }
    }



    .left {
        display: flex;
        text-transform: uppercase;
        gap: 2rem;


        h3 {
            color: white;
        }

        p {
            margin: 0.75rem 0;
            color: #959595;
            font-size: x-small
        }
    }

}

.contact {
    background-color: #303030;
    position: relative;

    .container {
        width: 80%;
        margin: auto;
        padding: 2rem;
        display: flex;
        justify-content: space-between;
        text-transform: uppercase;

    }

    .social {
        display: flex;
        gap: 0.75rem;


        h3 {
            color: #0282F9;
        }
    }

    a {
        text-decoration: none;
        color: white;
        padding: 0.50rem;
        border: 1px solid #0282F9;
    }


}
</style>