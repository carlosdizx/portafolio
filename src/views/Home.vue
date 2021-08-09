<template>
	<v-container>
		<v-card max-width="1000" class="mx-auto mb-12">
			<Info />
		</v-card>
		<v-card dark color="pink darken-5" max-width="800" class="mx-auto mb-12 pb-2">
			<v-card-title>Certificados y cursos</v-card-title>
			<Certificados />
		</v-card>
		<v-card dark color="pink darken-5" max-width="800" class="mx-auto mb-12">
			<ListadoProyectos />
		</v-card>

	</v-container>
</template>

<script lang="ts">
	import Vue from 'vue';
	import ListadoProyectos from '../components/ListadoProyectos.vue';
	import Info from '../components/Info.vue';
	import Certificados from '../components/Certificados.vue';

	export default Vue.extend({
		name: 'Home',
		components: { ListadoProyectos, Info,Certificados },
	});
</script>
