<template>
    <div class="shop-container">
        <div class="shop-text text-center lg:text-left lg:mx-6">
            <p class="over-title uppercase text-xs">Les boutiques Kipli</p>
            <h1 class="text-3xl mt-2">Venez à notre rencontre !</h1>
        </div>
        <div>

        </div>

<div class="lg:flex lg:justify-between">
    <div v-for="(shop, index) in shops" v-bind:key="index" class="shop-block lg:w-full lg:mx-5">
            <img class="h-96 w-full object-cover mb-5 mt-8" v-bind:src="shop.imgShop" alt="shop kipli">
            <p class="font-bold">{{ shop.title }}</p>
            <div class="uppercase my-3 text-sm">
                <p>{{ shop.address }}</p>
                <p>{{ shop.city }}</p>
                <p>tél. {{ shop.phone }}</p>
            </div>
            <a class="uppercase text-[#96503A] text-sm underline" v-bind:href="shop.link" target="_blank">Voir la boutique</a>      
        </div>
</div>

    </div>
</template>
<script>
    export default {
        name : 'ShopComponent',
        data() {
            return {
                shops : [
                    {
                    imgShop : 'https://res.cloudinary.com/kipli-cdn/image/upload/f_webp,q_auto/site/boutique/paris-boutique',    
                    title : 'La boutique Kipli Marais, Paris.', 
                    address : '59 rue du Temple', 
                    city : '75004 Paris, France', 
                    phone : '+33 (0)9 81 09 93 94',
                    link : 'https://kipli.com/fr/nos-boutiques'

                    },
                    {
                    imgShop : 'https://res.cloudinary.com/kipli-cdn/image/upload/f_webp,q_auto/site/boutique/lyon-boutique',    
                    title : 'La boutique Kipli, Lyon.', 
                    address : '25 rue de Brest', 
                    city : '69002 Lyon, France', 
                    phone : '+33 7 62 18 69 12',
                    link : 'https://kipli.com/fr/nos-boutiques'
                    },
                    {
                    imgShop : 'https://res.cloudinary.com/kipli-cdn/image/upload/f_webp,q_auto/site/boutique/toulouse',    
                    title : 'La boutique Kipli Marais, Toulouse.', 
                    address : '35 rue Lafayette', 
                    city : '31000 Toulouse, France', 
                    phone : '+33 7 61 22 06 02',
                    link : 'https://kipli.com/fr/nos-boutiques'
                    }
                ]
            }
        }
    }
</script>
<style></style>