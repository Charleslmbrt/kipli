<template>
    <div class="mb-20">
        <banner-component></banner-component>
        <div>
            <header-component></header-component>
            <p class="breadcrumb text-xs mt-6 px-5 lg:mx-11 lg:px-0">ACCUEIL / NOUS CONTACTER</p>
            <h4 class="primary-title text-3xl mt-3.5 px-5 lg:mx-11 lg:px-0">Nous contacter</h4>
        </div>

        <div class="lg:flex lg:justify-between lg:mx-11">
            <question-component></question-component>
            <div>
                <contact-component class="mt-12"></contact-component>
                <contact-form-component class="mt-24 px-5 lg:px-0 lg:mt-14"></contact-form-component>
            </div>
        </div>

        <shop-component class="mt-24 px-5 lg:mx-6 lg:px-0"></shop-component>
    </div>

</template>

<script>

//import components
import Banner from '../components/Banner.vue'
import Header from '../components/Header.vue'
import Question from '../components/Question.vue'
import Contact from '../components/Contact.vue'
import ContactForm from '../components/ContactForm.vue'
import Shop from '../components/Shop.vue'

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
        'contact-component' : Contact,
        'contact-form-component' : ContactForm,
        'shop-component' : Shop
    }
}
</script>

<style>
</style>