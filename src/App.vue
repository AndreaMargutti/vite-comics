<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
    data() {
        return {

        }
    },
    
    components: {
        AppHeader,
        AppMain,
        AppFooter
    }
}
</script>

<template>
    <div class="container">
        <AppHeader />
    </div>
    <AppMain />
    <AppFooter />
</template>

<style lang="scss">
    @use "style/general.scss"
</style>
