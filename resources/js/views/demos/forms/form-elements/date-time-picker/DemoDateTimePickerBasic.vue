<script setup>
import AppDateTimePicker from '@core/components/AppDateTimePicker.vue'

const date = ref('')
</script>

<template>
  <AppDateTimePicker
    v-model="date"
    label="Default"
  />
</template>
