<script>
export default {
    data() {
        return {
        }
    }
}
</script>

<template>

    <footer>
        <section id="socials-about-us">
            <div class="sign-in-btn">
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="socials-links">
                <h2>FOLLOW US</h2>
                <img src="../assets/img/footer-facebook.png" alt="facebook">
                <img src="../assets/img/footer-twitter.png" alt="twitter">
                <img src="../assets/img/footer-youtube.png" alt="youtube">
                <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                <img src="../assets/img/footer-periscope.png" alt="periscope">
            </div>
        </section>
    </footer>
</template>

<style lang="scss">

@import '../assets/scss/style.scss';

#socials-about-us {
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 22px;
}
.sign-in-btn button {
    background-color: transparent;
    border: 2px solid rgb(58, 160, 255);
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
}

.socials-links {
    display: flex;
    align-items: center;
}

.socials-links h2 {
    color: rgb(75, 183, 255);
    margin-right: 10px;
    padding: 20px;
}
</style>