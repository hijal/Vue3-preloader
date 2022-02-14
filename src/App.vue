<template>
	<Preloader />
</template>

<script>
import Preloader from './components/Preloader.vue';

export default {
	name: 'App',
	components: {
		Preloader,
	},
};
</script>

<style>
#app {
	position: absolute;
	left: 50%;
	top: 50%;
	margin: 0 auto;
}
</style>
