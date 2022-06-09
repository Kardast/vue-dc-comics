<template>
    <div class="comics-card">

        <img :src="details.thumb" :alt="details.series">
        <h4>{{details.series}}</h4>
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
.comics-card {
    margin: 5px 10px;
    img{
        width: 200px;
        height: 200px;
        object-fit: cover;
        object-position: top;
    }
    h4{
        width: 150px;
        margin: 15px 0;
    }
}
</style>