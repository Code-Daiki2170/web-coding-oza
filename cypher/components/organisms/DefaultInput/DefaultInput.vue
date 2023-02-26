<template>
	<input class="input" :type="props.type.Number" v-model="inputData" />
</template>

<script>
import { stringLiteral } from '@babel/types'
import { onMounted } from 'vue'

export default {
	name: 'DefaultInput',
	props: {
		input: {
			type: String | Number,
		},
	},
	setup() {
		const inputData = ref('')
		return { inputData }
	},
}
</script>

<style lang="scss" scoped>
input {
	width: 100%;
	border: solid 1px gray;
	background-color: #fff;
}
</style>
