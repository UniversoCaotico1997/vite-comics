<script>

export default {
    name: `SectionContent`
}

</script>




<template>
    <section class="content">
        <div class="container">
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
        </div>
    </section>
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



    }

}
</style>