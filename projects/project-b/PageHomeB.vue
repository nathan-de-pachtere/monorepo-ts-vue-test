<template>
	<div>Home B</div>
	<car-component />
	<bus-component />
	<dog-bus-component />
	<cat-car-component />
</template>

<script setup lang="ts">
import { defineAsyncComponent } from 'vue';
const CarComponent = defineAsyncComponent(() => import('@test/package-b/Car.vue'));
const BusComponent = defineAsyncComponent(() => import('@test/package-b/Bus.vue'));
const DogBusComponent = defineAsyncComponent(() => import('@test/package-c/DogBus.vue'));
const CatCarComponent = defineAsyncComponent(() => import('@test/package-c/CatCar.vue'));
</script>
