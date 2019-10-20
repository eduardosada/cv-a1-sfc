<template>
	<div id="MyApp">{{greetings}}</div>
</template>

<script>
export default {
	name: "app",

	data() {
		return {
			greetings: "¡Hola gente linda!"
		};
	}
};
</script>

<style>
#MyApp {
	font-family: "Avenir", Helvetica, Arial, sans-serif;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
	font-size: 2rem;
}
</style>
