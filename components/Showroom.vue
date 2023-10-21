<template>
     <div class="showroom">
            <h2 class="title2">
            Showroom
        </h2>
        <div class="content">
            <img src="/images/showroom.png" alt="">
            <div class="card">
                <h1>Notre Showrooms</h1>
                <p>n'hésitez pas a visité notre show room et de découvrir une large gamme de produits (vetements, accésssoires, mots neuves et occasions, et notre services entretient) une équipe experte et passionné vous attend.</p>
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