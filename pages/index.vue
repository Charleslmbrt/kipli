<template>
    <div>
<banner-component></banner-component>
    </div>
</template>
<script>

//import components
import Banner from '../components/Banner.vue'

export default {
    name : 'IndexPage',
    data() {
        return {

        }
    },
    components : {
        'banner-component' : Banner
    }
}
</script>
<style></style>