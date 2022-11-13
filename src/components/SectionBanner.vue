<script>
export default {
    name: `SectionBanner`,
    data() {
        return {
            icons: [
                {
                    image: `buy-comics-digital-comics.png`,
                    title: `Digital Comics`
                },
                {
                    image: `buy-comics-merchandise.png`,
                    title: `Dc Merchandise`
                },
                {
                    image: `buy-comics-shop-locator.png`,
                    title: `Subscription`
                },
                {
                    image: `buy-comics-subscriptions.png`,
                    title: `Comic Shop Locator`
                },
                {
                    image: `buy-dc-power-visa.svg`,
                    title: `Dc Power Visa`
                }
            ]
        }
    },
    methods: {
        getImageUrl(name) {
            return new URL(`../assets/img/${name}`, import.meta.url).href
        }
    }
}
</script>
 
<template>
    <section class="banner">
        <div class="container">
            <div class="info">
                <div class="square" v-for="icon in icons">
                    <img :src="getImageUrl(icon.image)" alt="">
                    <h5>{{ icon.title }}</h5>
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

        .info {
            display: flex;

            .square {
                display: flex;
                align-items: center;
                margin: 0 3rem;
                color: white;
                text-transform: uppercase;

                img {
                    width: 50px;
                    margin-right: 1rem;
                }
            }


        }

    }

}
</style>