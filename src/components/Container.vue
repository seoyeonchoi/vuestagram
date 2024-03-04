<template>
<div>
    <Post :insta="insta" v-for="(insta, i) in InstaData" :key=" i"/>
</div>
</template>

<script>
import Post from './Post.vue';

export default {
    name: 'Container-compo',
    components: {
        Post
    },
    props: {
        InstaData: Array,
    }

}
</script>

<style>

</style>