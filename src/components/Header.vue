<template>
    <header>
        <h1>Rapkhen</h1>
        <nav>
            <p class="header-home-btn">Home</p>
            <p>About Us</p>
            <p>Managment</p>
            <p>News & Event</p>
            <p>Gallery</p>
            <p>Contact us</p>
        </nav>
    </header>
</template>

<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<style scoped>
header {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    color: #000000;
}

nav {
    display: flex;
    justify-content: space-between;
    width: 40%;
}

.header-home-btn {
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    color: #FF9534;
}

p {
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    color: #000000;
}
</style>