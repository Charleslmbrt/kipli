<template>
    <div>
        <div class="header-container flex justify-between items-center mt-3 px-5 lg:mt-5">
             <div class="menu lg:hidden">
                <img class="w-7 h-4 " src="/menu-burger_02.svg" alt="menu-burger">
            </div>
            <div class="logo ml-3 lg:ml-0">
                <img class="w-[107px] h-[16px]" src="/logo-kipli.svg" alt="logo-kipli">
            </div>
  
    <div class="secondary-menu  hidden lg:block lg:flex">
        <p class="mr-5">Qui sommes-nous ?</p>
        <p class="mr-5">Nos ateliers</p>
        <p>Nos boutiques</p>
    </div>
   
            <div class="icons flex lg:hidden">
                <img class="w-4 h-4" src="/icon-message.svg" alt="icon-message">
                <img class="w-4 h-4 ml-1 lg:hidden" src="/icon-map.svg" alt="icon-map">
                <img class="w-4 h-4 ml-1" src="/icon-bell.svg" alt="icon-bell">
                <img class="w-4 h-4 ml-1" src="/icon-cart.svg" alt="icon-cart">
            </div>
    </div>

    <div class="sep h-px w-full bg-gray-300 my-5 hidden lg:block"></div>
    
    <div class="flex justify-between mr-5">
        <div class="menu-inline hidden lg:block lg:px-5">
        <ul class="flex">
            <li class="mr-10 uppercase text-xs" v-for="(cat, index) in categorys" v-bind:key="index">{{ cat }}</li>
         
        </ul>
    </div>
    <div class="icons hidden lg:block lg:flex">
        <img class="w-4 h-4" src="/icon-message.svg" alt="icon-message">
        <img class="w-4 h-4 ml-1 lg:hidden" src="/icon-map.svg" alt="icon-map">
        <img class="w-4 h-4 ml-1" src="/icon-bell.svg" alt="icon-bell">
        <img class="w-4 h-4 ml-1" src="/icon-cart.svg" alt="icon-cart">
    </div>
    </div>
   
    </div>
    
</template>
<script>
export default {
    name : 'HeaderComponent',
    data() {
        return {
            categorys : ['matelas', 'lit', 'couette', 'oreiller', 'linge de lit', 'canapé', 'mobilier', 'décoration']
        }
    }
}
</script>
<style></style>