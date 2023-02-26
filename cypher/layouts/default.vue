<template>
	<div class="l-wrapper">
		<DefaultInput></DefaultInput>
		<!-- <Header></Header>

		<NuxtPage /> -->
	</div>
</template>

<script>
import { Header } from '../components/organisms/Header'
import { DefaultInput } from '../components/organisms/ContactInput'
export default {
	components: { Header, DefaultInput },
}
</script>

<style lang="scss" scoped>
.l-wrapper {
	background-color: #eee;
}
</style>
