<template>
	<v-container>
		<v-card dark color="secondary lighten-1"max-width="800" class="mx-auto">
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
