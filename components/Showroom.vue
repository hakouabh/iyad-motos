<template>
     <div class="showroom">
            <h2 class="title2">
            Showroom
        </h2>
        <div class="content">
            <img src="/images/showroom.png" alt="">
            <div class="card">
                <h1>Notre Showrooms</h1>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text.</p>
                <a :href="link_facebook" class="btn">Learn more</a>
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