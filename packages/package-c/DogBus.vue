<template>
	<div>Dog Bus</div>
	<bus-component />
</template>

<script setup lang="ts">
import { defineAsyncComponent } from 'vue';
const BusComponent = defineAsyncComponent(() => import('@test/package-b/Bus.vue'));
</script>
