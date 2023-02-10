<template>
    <div>
    <h1>BEAUTY ReVeluv</h1>
    <button @click="Dior">new items</button>
    <ul>
    <li v-for ="Blink in Velvet" :key="Blink.id">
      {{ Blink.id }}  {{ Blink.brand }} {{ Blink.name }} </li>
        </ul>
    </div>
</template>

<script setup>
import axios from"axios";
import { ref } from"vue";

const Velvet = ref([]);
const url = ref("https://makeup-api.herokuapp.com/api/v1/products.json?brand=maybelline");
function Dior() {
    axios    
    .get(url.value)    
    .then((response) => {
        Velvet.value = response.data;    
    })    
    .catch((err) => {
        console.log(err);    
    });
}
</script>