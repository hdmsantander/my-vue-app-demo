<template>
	<div class="about">
		<vue-headful title="Vue.js Demo | About" description="About the web app" />
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
