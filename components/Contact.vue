<template>
  <div class="contact" id="contact">
    <h2 class="title2">
        contactez-nous
    </h2>
    <div class="contact-content">
            <div class="row">
                <h3>Coordonnées</h3>
                <div class="row_1">
                    <a class="info" href="tel: number_phone">{{ number_phone }}</a>
                    <a class="info" href="mailto: adresse_mail">{{ adresse_mail}}</a>
                    <a class="info adress">{{ adress_local }}</a>
                </div>
            </div>
            <div class="row">
                <h3>Réseaux sociaux</h3>
                <div class="row_2">
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
            adresse_mail : process.env.adresse_mail,
            adress_local : process.env.adress_local,
            link_facebook : process.env.link_facebook,
            link_insta : process.env.link_insta,
        }
    }

}
</script>

<style>

</style>