<template>
    <div>
        <h1>Index</h1>
        <p>Hello world</p>

    <DatePicker v-model="date" />
    </div>
</template>

<script setup>
import { ref } from 'vue';
import DatePicker from 'primevue/datepicker';

const date = ref(new Date());
</script>