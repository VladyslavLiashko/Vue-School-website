<template>
    <div class="team">
        <div class="our-team">
            <img src="../assets/Pattern.png" alt="">
            <h1>Meet Our Team</h1>
        </div>
        <div class="team-block">
            <TeamItem v-bind:item="item" />
        </div>
    </div>
</template>

<script>
import member1 from "../assets/teamMember1.png";
import member2 from "../assets/teamMember2.png";
import member3 from "../assets/teamMember3.png";

import fb from "../assets/fb.png";
import inst from "../assets/inst.png";
import wp from "../assets/wp.png";

import TeamItem from "./TeamItem.vue";
export default {
    data() {
        return {
            item: [
                { img: member1, name: "Afuwape J. Abiodun ", desc: "Headmaster", fb: fb, inst: inst, wp: wp },
                { img: member2, name: "Afuwape J. Abiodun ", desc: "Headmaster", fb: fb, inst: inst, wp: wp },
                { img: member3, name: "Afuwape J. Abiodun ", desc: "Teacher", fb: fb, inst: inst, wp: wp }
            ]
        }
    },
    components: {
        TeamItem
    }

}
</script>

<style scoped>
.team {
    max-width: 80%;
    margin: auto;
    background: #F2F2F2;
}

.our-team {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 5%;
}

.our-team h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 30px;
    color: #FF9534;
}

.team-block {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding-top: 5%;
}</style>