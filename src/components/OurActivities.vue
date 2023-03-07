<template>
    <div class="our-activities">
        <h1> <img src="../assets/Pattern.png" alt=""> Our Activities</h1>
        <div class="our-activities-wrapper">
            <OurActivitiesItem v-bind:item="item" />
        </div>

    </div>
</template>

<script>
import OurActivitiesItem from './OurActivitiesItem.vue';
import photo1 from "../assets/OurActivities.png"
import photo2 from "../assets/OurActivities2.png"
export default {
    data() {
        return {
            item: [
                { img: photo1, title: "Art & Creativity", body: "Art is the expression or application of human creative skill and imagination, typically in a visual form such as painting or sculpture, producing works to be appreciated primarily for their beauty or emotional power." },
                { img: photo2, title: "Sport & Entertainment", body: "Art is the expression or application of human creative skill and imagination, typically in a visual form such as painting or sculpture, producing works to be appreciated primarily for their beauty or emotional power." }
            ]
        }

    },
    components: {
        OurActivitiesItem
    }
}
</script>

<style scoped>
.our-activities {
    background: #F2F2F2;
    margin-left: 10%;
    margin-right: 10%;
    padding-top: 5%;
    padding-bottom: 5%;
}

h1 {
    margin-top: 0;
    font-style: normal;
    font-weight: 600;
    font-size: 30px;
    color: #FF9534;
    display: flex;
    align-items: center;
    justify-content: center;
}

.our-activities-wrapper {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding-top: 5%;
}
</style>