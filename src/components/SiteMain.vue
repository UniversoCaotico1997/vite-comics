<script>
import SectionBanner from "./SectionBanner.vue";
import SectionContent from "./RowThumbnails.vue";
import RowThumbnails from "./RowThumbnails.vue";


export default {
    name: `SiteMain`,
    components: {
        SectionBanner,
        SectionContent,
        RowThumbnails
    }

}

</script>


<template>

    <main id="site-main">
        <section class="content">
            <div class="container">

                <RowThumbnails></RowThumbnails>

            </div>
        </section>


        <SectionBanner></SectionBanner>


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
        color: white;
    }

}
</style>