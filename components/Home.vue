<template>
  <div class="home" id="home">
        <div class="content">
            <div class="left">
                <h1 class="title">IYAD <br> MOTOS</h1>
            <p>Ride in Style, Shop with Passion</p>
            <a href="#contact" class="btn">Contact</a>
            </div>
            <div class="right">
                <a :href="link_insta" target="_blank"><img src="/images/instagram.svg" alt=""></a>
                <a :href="link_facebook" target="_blank"><img src="/images/facebook.svg" alt=""></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            link_facebook : process.env.link_facebook,
            link_insta : process.env.link_insta,
        }
    }
}
</script>

<style>

</style>