<template>
    <div class="team-item" v-for="i in item">
        <div class="team-img">
            <img :src="i.img" alt="">
        </div>
        <div class="team-info">
            <h1>{{ i.name }}</h1>
            <p>{{ i.desc }}</p>
            <div class="team-media">
                <img :src="i.inst" alt="">
                <img :src="i.wp" alt="">
                <img :src="i.fb" alt="">
            </div>
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

.team-item{
    width: 20%;
    padding-bottom: 5%;
}
.team-img{
    border-radius: 145px;
    background-color: #fff;
    width: 45%;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    top: 3vw;
}
.team-img img{
    width: 90%;
}
.team-info {
    background: #FFFFFF;
    box-shadow: 0px -1px 10px 2px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    padding-top: 20%;
    padding-bottom: 5%;
}

.team-info h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 22px;
    color: #22343D;
    text-align: center;
}

.team-info p {
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    color: #FF725E;
    text-align: center;
}
.team-media{
    width: 50%;
    margin: auto;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
</style>