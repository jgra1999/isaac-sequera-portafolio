<script setup lang="ts">
import { onMounted, ref } from 'vue'
import { Design } from '../types/design'

interface Props {
	design: Design
}

defineProps<Props>()
</script>

<template>
	<img :src="design.img" alt="" />
</template>
