<script>
import SectionBanner from "./SectionBanner.vue";
import CardComics from "./CardComics.vue";
import Comics from "../assets/partials/js/comics";
import BgJumbotron from "./BgJumbotron.vue";
export default {
    name: `SiteMain`,
    components: {
        SectionBanner,
        CardComics,
        BgJumbotron
    },
    data() {
        return {
            comics: Comics
        }
    }


}

</script>


<template>

    <BgJumbotron></BgJumbotron>

    <div class="container">
        <div class="row">
            <CardComics v-for="item in comics" :image="item.thumb" :title="item.series" />
        </div>
    </div>
    <div class="load_more">
        <a href="#">load more</a>
    </div>

    <SectionBanner></SectionBanner>

</template>

<style lang="scss" scoped>
@use"../assets/partials/variable/container";
@use"../assets/partials/variable/variables" as *;


.row {
    margin-top: 1rem;
    display: flex;
    gap: 1rem;
    color: $dc-white;
}

.load_more {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 1.50rem;

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