<script setup lang="ts">
import DesignCard from './DesignCard.vue'
import data from '../designs.json'
</script>

<template>
	<section>
		<DesignCard v-for="design in data.designs" :design="design" />
	</section>
</template>
