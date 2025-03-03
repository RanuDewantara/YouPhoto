<script setup>
import Nav from './components/Nav.vue'
import Home from "./components/Home.vue";
import About from "./components/About.vue";
import Services from "./components/Services.vue";
import Portfolio from "./components/Portfolio.vue";
import Footer from "./components/Footer.vue";
import Contact from "./components/Contact.vue";

import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
onMounted(() => {
	initFlowbite();
})
</script>

<template>
	<Nav/>
	<Home/>
	<About/>
	<Services/>
	<Portfolio/>
	<Contact/>
	<Footer/>
</template>