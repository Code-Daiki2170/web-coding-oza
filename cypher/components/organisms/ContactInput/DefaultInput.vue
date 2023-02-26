<template>
	<div><input type="text" v-model="inputData" /></div>
</template>

<script>
import { stringLiteral } from '@babel/types'
import { onMounted } from 'vue'

export default {
	name: 'DefaultInput',
	props: {
		text: {
			type: String | Number,
			required: true,
		},
	},

	setup() {
		const inputData = ref('')
		return { inputData }
	},
}
</script>

<style lang="scss" scoped></style>
