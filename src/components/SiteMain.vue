<script>
import SectionBanner from "./SectionBanner.vue";
import SectionContent from "./SectionContent.vue";

export default {
    name: `SiteMain`,
    components: {
        SectionBanner,
        SectionContent
    }

}

</script>


<template>

    <main id="site-main">


        <SectionContent></SectionContent>


        <SectionBanner></SectionBanner>


    </main>

</template>

<style lang="scss" scoped>

</style>