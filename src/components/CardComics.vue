<script>
export default {
    name: `CardComics`,
    props: {
        image: String,
        title: String
    }
}
</script>




<template>
    <div class="col">
        <img :src="image">
        <h3>{{ title }}</h3>
    </div>
</template>





<style lang="scss" scoped>
h3 {
    margin-top: 0.50rem;
}
</style>