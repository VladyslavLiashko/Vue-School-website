<template>
    <div class="our-activity-item" v-for="i in item">
        <img :src="i.img">
        <div>
            <h1>{{ i.title }}</h1>
            <p>{{ i.body }}</p>
        </div>

    </div>
</template>

<script>
export default {
    props: {
        item: {
            type: Array,
            required: true
        }
    }
}
</script>

<style scoped>
.our-activity-item {
    display: flex;
    width: 40%;
    align-items: center;
}
img{
    height: 100%;
    width: 50%;
    margin-right: 5%;
}
div{
    height: 100%;
}
h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 25px;
    color: #22343D;
}

p {
    font-style: normal;
    font-weight: 400;
    font-size: 17px;
    line-height: 176%;
    color: #22343D;
}
</style>