<script setup>
import navbar from './components/navbar.vue';
import Footer from './components/footer.vue';
import Header from './components/header.vue';

</script>

<template>
    <v-app>
        <navbar></navbar>
        <header/>
       <main>
           <RouterView></RouterView>
       </main>
       <Footer/>
       </v-app>
</template>

