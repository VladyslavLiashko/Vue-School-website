<template>
    <div class="footer-form">
        <div class="footer-form-wrapper">
            <h1>Better <b>education</b> for a better world <br>An <b>investment</b> in <b>knowledge</b> pays the best
                <b>interest.</b>
            </h1>
            <form action="#">
                <input type="text" placeholder="Enter Email to recive news letter">
                <button> <img src="../assets/tg.png" alt=""></button>
            </form>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer-form {
    background: url(../assets/footer.png);
    background-repeat: no-repeat;
    background-size: cover;
    width: 80%;
    margin: auto;

}

.footer-form-wrapper {
    background: rgba(0, 0, 0, 0.4);
    padding-top: 5%;
    padding-bottom: 5%;
}

.footer-form h1 {
    font-style: normal;
    font-weight: 500;
    font-size: 30px;
    line-height: 167%;
    color: #FFFFFF;
    text-align: center;

}

.footer-form b {
    color: #FF9534;
}

form {
    max-width: 80%;
    margin: auto;
    display: flex;
    justify-content: center;
    margin-top: 5%;
}

form input {
    background: rgba(0, 0, 0, 0.4);
    border: 2px solid #FFFFFF;
    border-right: none;
    border-top-left-radius: 40px;
    border-bottom-left-radius: 40px;
    width: 70%;
    height: 4vw;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    color: #FFFFFF;
}

form button {
    background: #FF9534;
    border-radius: 0px 40px 40px 0px;
    border: 2px solid #FFFFFF;
    border-left: none;
    display: flex;
    align-items: center;
    justify-content: center;
}

form button img {
    width: 80%;
}
</style>