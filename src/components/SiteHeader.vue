<script>

export default {
    name: `SiteHeader`,
    data() {
        return {
            menu: [
                {
                    text: `characters`,
                    herf: `#`
                },
                {
                    text: `comics`,
                    herf: `#`
                },
                {
                    text: `movies`,
                    herf: `#`
                },
                {
                    text: `tv`,
                    herf: `#`
                },
                {
                    text: `games`,
                    herf: `#`
                },
                {
                    text: `collectibles`,
                    herf: `#`
                },
                {
                    text: `videos`,
                    herf: `#`
                },
                {
                    text: `fans`,
                    herf: `#`
                },
                {
                    text: `news`,
                    herf: `#`
                },
                {
                    text: `shop`,
                    herf: `#`
                },
            ]
        }

    }
}

</script>


<template>
    <header id="site-header">
        <div class="container">

            <div class="box_left">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <!-- /.box_left -->

            <div class="box_right">
                <ul v-for="item in menu">
                    <li>
                        <a href="#">{{ item.text }}</a>
                    </li>
                </ul>


            </div>
            <!-- /.box_right -->
        </div>
        <!-- /.container -->

    </header>
</template>

<style lang="scss" scoped>
.container {
    width: 80%;
    margin: auto;
    padding: 1rem;
    display: flex;
    justify-content: space-between;

    img {
        width: 60%;
    }
}

.box_right {
    align-self: center;
    display: flex;

    ul {
        list-style-type: none;
    }

    a {
        text-decoration: none;
        margin: 0 1rem;
        color: black;
        text-transform: uppercase;
        font-size: small;

        &:hover {
            color: #0282F9;
        }
    }
}
</style>