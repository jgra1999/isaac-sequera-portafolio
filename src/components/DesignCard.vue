<script setup lang="ts">
import { Design } from '../types/design'

interface Props {
	design: Design
}

defineProps<Props>()
</script>

<template>
	<img :src="design.img" alt="" loading="lazy" />
</template>
