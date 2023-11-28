
<template>
  <!-- <HellowordVue :user="user" /> -->
  <HellowordVue/>
  <div class="text-green">
    {{ user.name }}
  </div>
</template>


<script setup>
import HellowordVue from './components/Helloword.vue';
import { reactive } from 'vue';

const user = reactive({ name: "Israël", level: 6 });

const display = () => {
  console.log(user.name, user.level);
}
</script>

<style scoped>
.text-red{
    color: red;
}

.text-green{
    color: green;
}
</style>
