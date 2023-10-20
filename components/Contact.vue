<template>
  <div class="contact" id="contact">
    <h2 class="title">
        contactez-nous
    </h2>
    <div class="contact-content">
            <div class="row">
                <h3>Numéro téléphone</h3>
                <div class="row_1">
                    <a href="tel: number_phone">{{ number_phone }}</a>
                    <a href="tel: number_phone">{{ number_phone }}</a>
                    <a href="tel: number_phone">{{ number_phone }}</a>
                </div>
            </div>
            <div class="row">
                <h3>Réseaux sociaux</h3>
                <div class="row_1">
                    <a class="social-link" target="_blank" :href="link_insta"><img src="/images/instagram.svg" alt="">Instagram</a>
                    <a class="social-link" target="_blank" :href="link_facebook"><img src="/images/facebook.svg" alt="">Facebook</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            number_phone : process.env.number_phone,
            link_facebook : process.env.link_facebook,
            link_insta : process.env.link_insta,
        }
    }

}
</script>

<style>

</style>