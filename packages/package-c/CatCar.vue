<template>
	<div>Cat Car</div>
	<car-component />
</template>

<script setup lang="ts">
import { defineAsyncComponent } from 'vue';
const CarComponent = defineAsyncComponent(() => import('@test/package-b/Car.vue'));
</script>
