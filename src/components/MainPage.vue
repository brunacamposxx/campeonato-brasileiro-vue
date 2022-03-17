<template>
	<v-container>
		<h2>Brasileirão Série A</h2>
		<v-img src="https://diariodonordeste.verdesmares.com.br/image/contentid/policy:1.2974821:1596806515/Serie-A.png" />
		<p>O Campeonato Brasileiro de Futebol, também conhecido como Campeonato Brasileiro, Brasileirão e Série A, é a liga brasileira de futebol profissional entre clubes do Brasil, sendo a principal competição futebolística no país.</p>
	</v-container>
</template>

<script>
export default {
	name: 'MainPage',

	data: () => ({
		//
	}),
}
</script>

<style>
img {
	width: 100%;
	padding: 10px;
}
p {
	text-align: justify;
	font-weight: bold;
}
h2 {
	text-align: center;
}
</style>