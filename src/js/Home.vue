<template>
	<div>
		<span class="cont">Página Home: {{cont}}</span>
		
		<ul>
			<li>
				<router-link to="/user/1">Usuário 1</router-link> -
				<router-link to="/user/1/perfil">Perfil</router-link> -
				<router-link to="/user/1/posts">Posts</router-link>
			</li>
			<li>
				<router-link to="/user/2">Usuário 2</router-link> - 
				<router-link to="/user/2/perfil">Perfil</router-link> -
				<router-link to="/user/2/posts">Posts</router-link>
			</li>
		</ul>
		
	</div>
</template>

<script>
	export default {
		data() {
			return {
				cont:'Conteúdo da página home'
			}
		}
	}
</script>

<style>
	.cont {
		color:#0000FF;
	}
</style>