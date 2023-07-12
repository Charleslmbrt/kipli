<template>
    <div>
       <h1 class="text-3xl">Formulaire de contact</h1> 
       <form class="flex flex-col">
        <select  class="h-14 p-3.5 my-8 drop-shadow-md text-[#314D3CCC] placeholder-gray-400 rounded-md">
            <option>Sujet</option>
            <option>Sujet 2</option>
            <option>Sujet 3</option>
        </select>

        <div class="lg:flex lg:justify-between">
            <div class="flex flex-col lg:flex-col lg:w-1/2 lg:mr-5">
             <input class="h-14 p-3.5 mb-8 drop-shadow-md text-[#314D3CCC] placeholder-[#314D3CCC] rounded-md" type="text" placeholder="Nom">
             <input class="h-14 p-3.5 mb-8 drop-shadow-md text-[#314D3CCC] placeholder-[#314D3CCC] rounded-md" type="text" placeholder="Email">
            </div>

            <div class="flex flex-col lg:flex-col lg:w-1/2 lg:ml-5">
             <input class="h-14 p-3.5 mb-8 drop-shadow-md text-[#314D3CCC] placeholder-[#314D3CCC] rounded-md" type="text" placeholder="Prénom">
             <input class="h-14 p-3.5 mb-8 drop-shadow-md text-[#314D3CCC] placeholder-[#314D3CCC] rounded-md" type="text" placeholder="Téléphone">
            </div>
        </div>

        <input class="h-14 p-3.5 mb-8 drop-shadow-md text-[#314D3CCC] placeholder-[#314D3CCC] rounded-md" type="text" placeholder="Numéro de commande">
        <textarea class="h-56 p-3.5 mb-8 drop-shadow-md text-[#314D3CCC] placeholder-[#314D3CCC] rounded-md" placeholder="Message..."></textarea>
       </form>
    </div>
</template>
<script>
    export default {
        name : 'ContactForm'
    }
</script>
<style></style>