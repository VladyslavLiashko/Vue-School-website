<template>
    <div class="blog">
        <div class="latest-blog">
            <img src="../assets/Pattern.png" alt="">
            <h1>Latest Blog</h1>
        </div>
        <BlogItem v-bind:item="item" />
    </div>
</template>

<script>
import BlogItem from './BlogItem.vue';
import img from "../assets/Blog.png"
import img2 from "../assets/Blog2.png"
export default {
    data() {
        return {
            item: [
                { img: img, body: "Lorem ipsum dolor sit met, consectetur cing elit, sed do abbey...", name: "Headmaster", mes: 10, eye: 29, date: "September 10, 2021" },
                { img: img2, body: "Lorem ipsum dolor sit met, consectetur cing elit, sed do abbey...", name: "Headmaster", mes: 10, eye: 29, date: "September 10, 2021" }
            ]
        }
    },
    components: {
        BlogItem
    }
}
</script>

<style scoped>
.blog {
    display: flex;
    justify-content: space-around;
    max-width: 80%;
    margin: auto;
    padding-top: 5%;
    padding-bottom: 5%;
}

.latest-blog {
    width: 30%;
    display: flex;
    align-items: center;
    justify-content: right;
}

.latest-blog h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 30px;
    color: #FF9534;
}
</style>