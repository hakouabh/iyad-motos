<template>
    <div class="Scroll">
          <button class="btnScroll">
              <i class="fa fa-arrow-up" aria-hidden="true"></i>
          </button>
      </div>
  </template>
  
  <script>
  export default {
      mounted(){
      const btnScroll = document.querySelector(".btnScroll");
  
  btnScroll.addEventListener("click", function () {
     window.scrollTo({
          top: 0,
          left: 0,
          behavior: "smooth"
      }); 
      
  });
  }
  }
  </script>
  