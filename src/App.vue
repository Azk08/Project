<template>
    <div class="header">
        <LandingPage />
    </div>

    <NavigationBar />
    <div class="about">
        <AboutPage />
    </div>

    <ContactPage />
    <!-- <CataloguePage/> -->
    <FooterPage />
</template>



<script setup>
import LandingPage from './components/LandingPage.vue';
import NavigationBar from './components/NavigationBar.vue';
import AboutPage from './components/AboutPage.vue';
import ContactPage from './components/ContactPage.vue';
import FooterPage from './components/FooterPage.vue';
// import CataloguePage from './components/CataloguePage.vue';
</script>
<style scoped>
/* *{
    font-family: sans-serif;
} */
@media screen and (max-width :780px) {
    .about {
        display: none;
    }
    footer{
        display: none;
    }
}
</style>