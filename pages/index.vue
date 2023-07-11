<template>
    <div>
        <banner-component></banner-component>
        <div class="px-3.5">
            <header-component></header-component>
            <p class="breadcrumb text-xs mt-6">ACCUEIL / NOUS CONTACTER</p>
            <h4 class="primary-title text-3xl mt-3.5">Nous contacter</h4>
        </div>
        <question-component></question-component>
    </div>

</template>

<script>

//import components
import Banner from '../components/Banner.vue'
import Header from '../components/Header.vue'
import Question from '../components/Question.vue'
import Contact from '../components/Contact.vue'

export default {
    name : 'IndexPage',
    data() {
        return {

        }
    },
    components : {
        'banner-component' : Banner,
        'header-component' : Header,
        'question-component': Question,
        'contact-component' : Contact
    }
}
</script>

<style>
</style>