<template>
   <div class="main">
      <div class="start">
         <div class="start__menu">
            <div class="menu__logo"><img src="../images/place-your-logo-here-double-click-to-edit.png" alt="" class="menu__img"></div>
            <div v-for="item in ['Home', 'Product', 'Promo', 'Anout', 'Contact']" :key="item" class="menu__item">{{item}}</div>
            <img src="../images/search.png" alt="" class="menu__search">
         </div>
         <div class="start__discount">Discount 50%</div>
         <div class="start__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum. </div>
         <button class="start__button">Order now</button>
      </div>

      <div class="popular">
         <div class="popular__title">Popular menu</div>
         <div class="popular__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum. </div>
         
         <div class="popular__cards">
            <div class="popular__card">
               <img src="../images/image1.png" alt="" class="card__img">
               <div class="card__title">Package I</div>
               <div class="card__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
               

            </div>
               <div class="popular__card">
                  <img src="../images/image2.png" alt="" class="card__img">
                  <div class="card__title">Package II</div>
                  <div class="card__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
               </div>
               
               <div class="popular__card">
                  <img src="../images/image3.png" alt="" class="card__img">
                  <div class="card__title">PACKAGE III</div>
                  <div class="card__text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
               </div>
         </div>


      </div>
   </div>
</template>

<script>
export default {
   data() {
      return {
      }
   },
   components: {
   }
}
</script>
