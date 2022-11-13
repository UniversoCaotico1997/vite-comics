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
    <div class="menu">
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
    </div>
</template>

<style lang="scss" scoped>
@use"../assets/partials/variable/container";
@use"../assets/partials/variable/variables" as *;

.menu {
    background-color: $dc-white;
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
            color: $dc-primary;
        }
    }
}
</style>