<script setup lang="ts">
import Select from '../src/select.vue'
import SelectGeneric from '../src/select-generic.vue'
</script>

<template>
  <Select :multiple="false" :multiple-limit="5" />
  <SelectGeneric :multiple="false" :multiple-limit="5" />
  <SelectGeneric multiple :multiple-limit="5" />
</template>

<style scoped></style>
