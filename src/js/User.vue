<template>
	<div>
		<h4 class="userPage">Página do Usuário</h4>
		<span class="userId">ID do usuário: {{$route.params.id}}</span>

		<hr />

		<router-view></router-view>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		}
	}
</script>

<style>
	.userPage {
		color:#000000;
	}
	.userId {
		color:#00FF00;
	}
</style>