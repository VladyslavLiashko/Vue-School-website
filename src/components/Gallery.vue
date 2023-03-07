<template>
    <div class="gallery">
        <div class="gallery-wrapper">
            <div class="gallery-logo">
                <img src="../assets/Pattern.png" alt="">
                <h1>Our Gallery</h1>
            </div>
            <div class="gallery-img"><img src="../assets/Gallery1.png" alt=""></div>
            <div class="gallery-img"><img src="../assets/Gallery2.png" alt=""></div>
        </div>
        <div class="gallery-btn">
            <button>More Articles -></button>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.gallery {
    width: 80%;
    margin: auto;
    padding-top: 5%;
    padding-bottom: 5%;
}

.gallery-wrapper {
    display: flex;
    justify-content: space-around;
}

.gallery-logo h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 30px;
    color: #FF9534;
}

.gallery-logo {
    display: flex;
    align-items: center;
    justify-content: right;
}

.gallery-logo img {
    width: 20%;
}

.gallery-img img {
    width: 100%;
}

.gallery-btn {
    display: flex;
    justify-content: right;
    padding-right: 7%;
    padding-top: 5%;
}

button {
    background: #FF9534;
    border-radius: 5px;
    border: none;
    width: 15%;
    height: 3vw;

    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 105%;
    letter-spacing: -0.02em;
    color: #FFFFFF;
}</style>