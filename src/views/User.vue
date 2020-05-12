<template>
	<div id="user">
		<h1>The user page!</h1>
		<h3>This page is a new route called user.</h3>
		<p>
			The paragraphs of this page are in italics, notice that if you switch to a
			different page the styles are bounded to the specific page, this is due to
			the parameter "scoped" being in the "style" section.
		</p>
		<p>Some info passed to this page:</p>
		<p>Username: {{ username }}</p>
		<app-info></app-info>
	</div>
</template>

<script>
import Info from '@/components/Info.vue';
export default {
	data() {
		return {
			username: 'Fabian',
		};
	},
	components: {
		'app-info': Info,
	},
};
</script>

<style scoped>
p {
	font-style: italic;
}
</style>
