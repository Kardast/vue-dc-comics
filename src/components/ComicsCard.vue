<template>
    <div class="comics-card">

        <img :src="details.thumb" :alt="details.series">
    </div>
</template>

<script>

export default {
    name: 'ComicsCard',
    // inserire le props
    props: {
        details: Object
    }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
// .comics-card {

// }
</style>