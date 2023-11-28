
<template>
<HellowordVue :nom="nom"/>
</template>


<script setup>
import HellowordVue from './components/Helloword.vue';

const nom = "Israël";
</script>

<style scoped>
</style>
