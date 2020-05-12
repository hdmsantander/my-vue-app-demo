<template>
	<div class="about">
		<h1>This is an about page!</h1>
		<app-helloworld msg="Welcome to a Vue.js App"></app-helloworld>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
export default {
	name: 'About',
	components: {
		'app-helloworld': HelloWorld,
	},
};
</script>
