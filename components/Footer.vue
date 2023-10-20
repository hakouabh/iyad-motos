<template>
   <div class="footer">
        <div class="row_1">
            <div class="col_1">
                <img class="logo" src="/images/logo_footer.svg" alt="">
                <div class="social_link">
                    <a target="_blank" :href="link_facebook"><img src="/images/fcbk.svg" alt=""></a>
                    <a target="_blank" :href="link_insta"><img src="/images/insta.svg" alt=""></a>
                </div>
            </div>
            <div class="col_2">
                <h3>Navigation</h3>
                <a href="#home">Accueil</a>
                <a href="#apropos">A propos</a>
                <a href="#Entretien">Entretien</a>
                <a href="#nosmarques">Nos marques</a>
                <a href="#contact">Contact</a>
            </div>
            <div class="col_2">
                <h3>Coordonnées</h3>
                <p>{{adress_local}}</p>
            </div>
        </div>
        <div class="row_2">
            <p>copyright &copy; 2023 | Tous les droits sont réservés.</p>
            <p>BY <a href="https://www.developily.com/" target="_blank">DEVELOPILY</a></p>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            adress_local : process.env.adress_local,
            link_facebook : process.env.link_facebook,
            link_insta : process.env.link_insta,
        }
    }
}
</script>

<style>

</style>