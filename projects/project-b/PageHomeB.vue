<template>
	<div>Home B</div>
	<car-component />
	<bus-component />
</template>

<script setup lang="ts">
import { defineAsyncComponent } from 'vue';
const CarComponent = defineAsyncComponent(() => import('@test/package-b/Car.vue'));
const BusComponent = defineAsyncComponent(() => import('@test/package-b/Bus.vue'));
</script>
