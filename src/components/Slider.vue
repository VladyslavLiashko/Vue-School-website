<template>
    <div class="slider">
        <div class="slider-wrapper">
            <h1>A wonderful <b>first</b> out of home learning <br>
                <b>Experience</b> For you Child.
            </h1>
            <button>More Info -></button>
        </div>
    </div>
</template>

<script>
export default{

}
</script>

<style scoped>
.slider {
    background: url(../assets/slider1.png);
    background-size: 100%;
    background-repeat: no-repeat;
    height: 30vw;
    margin-left: 10%;
    margin-right: 10%;
}
.slider-wrapper{
    background: rgba(0, 0, 0, 0.5);
    padding: 10%;
    height: 100%;
}

h1 {
    font-style: normal;
    font-weight: 500;
    font-size: 41px;
    color: #FFFFFF;
}

b {
    color: #FF9534;
}

button {
    background: #FF9534;
    border-radius: 5px;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    color: #FFFFFF;
    border: none;
    height: 20%;
    width: 15%;
    margin-top: 5%;
}
</style>