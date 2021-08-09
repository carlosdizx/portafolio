<template>
	<v-container>
		<v-card dark color="pink darken-4" max-width="900" class="mx-auto">
			<ListadoProyectos />
		</v-card>
	</v-container>
</template>

<script lang="ts">
	import Vue from 'vue';
	import ListadoProyectos from '../components/ListadoProyectos.vue';

	export default Vue.extend({
		name: 'Home',
		components: { ListadoProyectos },
	});
</script>
