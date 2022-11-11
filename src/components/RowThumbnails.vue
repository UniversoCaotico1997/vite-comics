<script>
// import { } from "./Thumbnails.vue";
export default {
    name: `RowThumbnails`,
    // components: {
    //     thumbnails
    // }
}

</script>




<template>
    <div class="row" v-for="item in thumbnails">
        <div class="col">
            <img :src="item.thumb" alt="">
            <h3>{{ item.type }}</h3>
        </div>
        <!-- /.col -->
    </div>
    <!-- /.row -->
</template>





<style lang="scss" scoped>
.row {
    display: flex;
    gap: 1rem;
}

.col {
    width: calc(100% / 6);

    h3 {
        margin-top: 0.50rem;
    }
}
</style>