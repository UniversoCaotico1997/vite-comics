<script>
import SectionBanner from "./SectionBanner.vue";

export default {
    name: `SiteMain`,
    components: {
        SectionBanner
    }

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


        h3 {
            color: white;
        }
    }

}
</style>