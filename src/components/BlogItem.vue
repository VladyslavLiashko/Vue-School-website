<template>
    <div class="blog-item" v-for="i in item">
        <img class="blog-item-img" :src="i.img" alt="">
        <div class="blog-item-wrapper">
            <div class="blog-item-info">
                <p>{{ i.body }}</p>
                <div class="blog-item-statistic">
                    <p>{{ i.name }}</p>
                    <div class="statistic-item">
                        <img src="../assets/comments.png" alt="#">
                        <span>{{ i.mes }}</span>
                    </div>
                    <div class="statistic-item">
                        <img src="../assets/eye.png" alt="#">
                        <span>{{ i.eye }}</span>
                    </div>

                </div>
            </div>
            <p> {{ i.date }}</p>
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
.blog-item {
    background: #FFFFFF;
    box-shadow: 0px 0px 20px 2px rgba(0, 0, 0, 0.2);
    border-radius: 10px;
    width: 22.7%;
}

.blog-item-wrapper {
    width: 80%;
    margin: auto;
}

.blog-item-img {
    width: 100%;
}

.blog-item-info p {
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 160%;
    color: #000000;
}

.blog-item-statistic {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.blog-item-statistic p {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 160%;
    /* or 160% */
    color: #000000;
}

.statistic-item {
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.statistic-item img{
    margin-right: 20%;
}
</style>