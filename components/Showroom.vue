<template>
     <div class="showroom">
            <h2 class="title2">
            Showroom
        </h2>
        <div class="content">
            <img src="/images/showroom.png" alt="">
            <div class="card">
                <h1>Notre Showrooms</h1>
                <p>n'hésitez pas à visiter notre showroom et de découvrir une large gamme de produits (vêtements, accésssoires, motos neuves , occasions, et notre service entretien) une équipe experte et passionné vous attend.</p>
                <a :href="link_facebook" target="_blank" class="btn">Learn more</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            link_facebook : process.env.link_facebook,
        }
    }
}
</script>

<style>

</style>