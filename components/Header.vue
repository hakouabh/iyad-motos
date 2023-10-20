<template>
  <div class="header">
        <img class="logo" src="/images/logo.svg" alt="">
        <ul class="navbar">
            <li><a href="#home" class="link">Accueil</a></li>
            <li><a href="#about" class="link">A propos</a></li>
            <li><a href="#shop" class="link">Boutique</a></li>
            <li><a href="#contact" class="link">Contact</a></li>
        </ul>
        <div id="menu-btn" class="fa fa-bars menu-btn"></div>
    </div>
</template>

<script>
export default {
  mounted(){
    let menu = document.querySelector(' #menu-btn');
    let navbar = document.querySelector(' .header .navbar');
    menu.onclick = () => {
        menu.classList.toggle('fa-times');
        navbar.classList.toggle('active');
    }
    window.onscroll = () =>{
        menu.classList.remove('fa-times');
        navbar.classList.remove('active');
    }
    //sticky
    const header = document.querySelector(".header");
    window.addEventListener("scroll", function() {
      header.classList.toggle ("sticky",window.scrollY > 100);
    });

  }
}
</script>

<style>

</style>