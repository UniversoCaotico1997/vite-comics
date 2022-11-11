<script>

export default {
    name: `RowThumbnails`
}

</script>




<template>
    <div class="row">
        <div class="col">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis facilis natus quae tempore
            eaque est impedit quaerat tempora aperiam sit praesentium voluptate, suscipit autem eos quidem
            officia, accusantium ex cum?
            <h3>Titolo</h3>
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