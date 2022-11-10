<script>

export default {
    name: `SiteHeader`
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
                <a href="#">characters</a>
                <a href="#">comics</a>
                <a href="#">movies</a>
                <a href="#">tv</a>
                <a href="#">games</a>
                <a href="#">collectibles</a>
                <a href="#">videos</a>
                <a href="#">fans</a>
                <a href="#">news</a>
                <a href="#">shop</a>
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

    a {
        text-decoration: none;
        margin: 0 1rem;
        color: black;
        text-transform: uppercase;
        font-size: small;
    }
}
</style>