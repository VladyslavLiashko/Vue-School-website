<template>
    <div class="footer">
        <footer>
            <div class="footer-logo-block">
                <h1>Logo</h1>
                <p>Rapkhen is an outstanding Nursery & Primary school targeting educational System, helping Kids to read and
                    write and to establish strong identity.</p>
            </div>
            <div class="footer-info-block">
                <h1>Links</h1>
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Management</li>
                    <li>News&Event</li>
                    <li>Gallery</li>
                    <li>Contact us</li>
                </ul>
            </div>
            <div class="footer-info-block">
                <h1>Find Us</h1>
                <div class="footer-block-nav">
                    <img src="../assets/compas.png" alt="">
                    <p>Lorem ipsum dolor siter <br> amet, consectetur adipising <br> elitsed do sum.</p>
                </div>
                <div class="footer-block-nav">
                    <img src="../assets/mail.png" alt="">
                    <p>Loremipilum11@gmail.com</p>
                </div>
                <div class="footer-block-nav">
                    <img src="../assets/phone.png" alt="">
                    <p> +234 805 029 1265 <br> +234 907 228 0656</p>
                </div>
            </div>
            <div class="footer-info-block">
                <h1>Social Contact</h1>
                <div class="networks">
                    <img src="../assets/fb-black.png" alt="">
                    <p>Facebook</p>
                </div>
                <div class="networks">
                    <img src="../assets/tw.png" alt="">
                    <p>Twitter</p>
                </div>
                <div class="networks">
                    <img src="../assets/inst-black.png" alt="">
                    <p>Instagram</p>
                </div>
                <div class="networks">
                    <img src="../assets/wp-black.png" alt="">
                    <p>Whats up</p>
                </div>
                <div class="networks">
                    <img src="../assets/tg-black.png" alt="">
                    <p>Telegram</p>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
footer {
    padding-top: 5%;
    display: flex;
    justify-content: space-between;
    max-width: 80%;
    margin: auto;
}

.footer-logo-block {
    width: 20%;
}

.footer-logo-block p {
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 160%;
    color: #000000;
}

.footer-info-block h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 25px;
    color: #FF9534;
}

.footer-info-block p {
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 105%;

    letter-spacing: -0.02em;

    color: #000000;

}

.footer-info-block ul {
    padding: 0;
    margin: 0;
}

.footer-info-block ul li {
    list-style: none;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 105%;

    letter-spacing: -0.02em;

    color: #000000;
    padding-bottom: 20%;
}
.footer-block-nav{
    display: flex;
    align-items: center;
}
.footer-block-nav img{
    width: 10%;
    margin-right: 10%;
}
.networks{
    display: flex;
    align-items: center;
}
.networks img{
    width: 10%;
    margin-right: 10%;
}
</style>