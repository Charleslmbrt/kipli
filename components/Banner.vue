<template>
    <div class="container-banner flex justify-between items-center bg-[#314D3C] text-[#fffbf8] h-11 w-full px-5 text-xs tracking-[0.25em]">
     <div class="notice flex items-center">
      <div class="notice-stars flex mr-2">
        <img class="w-3 h-3" src="/star.svg" alt="star 1">
        <img class="w-3 h-3" src="/star.svg" alt="star 2">
        <img class="w-3 h-3" src="/star.svg" alt="star 3">
        <img class="w-3 h-3" src="/star.svg" alt="star 4">
        <img class="w-3 h-3" src="/star.svg" alt="star 5">
      </div>
      <div class="notice-txt">4.8/5 sur 4.312 avis</div>
     </div>
     <p class="benefits hidden lg:block">
     Livraison gratuite | Paiement 3x sans frais matelas | garanti 10 ans
     </p>
     <p class="lg:hidden">|</p>
     <p class="phone-number">
     +33 (0)1 76 42 11 72
     </p>

    </div>
</template>
<script>
export default {
    name : 'BannerComponent'
}
</script>
<style></style>