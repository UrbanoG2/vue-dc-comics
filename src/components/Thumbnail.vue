<template>
    <div>
        <div class="thumb-img">
            <img :src="img" :alt="name">
        </div>
        <h2> {{ name }} </h2>
    </div>
</template>

<script>
export default {
    name:"Thumbnail",
    props:{
        img: String,
        name: String,
    }
}
</script>

<style lang="scss">
    .thumb-img {
        width: 120px;
        aspect-ratio: 1;
        overflow: hidden;
        img {
            width:100%;
        }
    }

    h2 {
        color: white;
        text-transform: uppercase;
        font-size: 0.8em;
        padding-top: 1em;
        width: 120px;
    }
</style>