<template>
	<div id="app">
		<header>
			<div id="branding">
				
			    <h1>Laravel & Vue.js App</h1>
			</div>
		</header>
		<hr>
		<router-view></router-view>
	</div>
</template>

<script>
	import UserTable from './components/users/UsersTable.vue';

	export default {
		components: {
			UserTable
		},
		methods: {
			goHome(){
				this.$router.push({name: 'home'});
			}
		}
	}	
</script>

<style>
#app {
	width: 70%;
	margin: auto;
}

#branding {
	display: flex;
	align-items: center;
	justify-content: center;
	padding: 2em;
}


</style>
