<script>
export default {
    name: `BgJumbotron`

}
</script>

<template>
    <div class="jumbotron">
        <div class="current_series">
            <a href="#">current series</a>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use"../assets/partials/variable/variables" as *;

.jumbotron {
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
    height: 350px;
    position: relative;

    .current_series {
        position: absolute;
        bottom: -10px;
        left: 170px;
    }

    a {
        text-decoration: none;
        text-transform: uppercase;
        color: $dc-white;
        padding: 0.50rem 2rem;
        border: 1px solid $dc-primary;
        background-color: $dc-primary;
    }
}
</style>