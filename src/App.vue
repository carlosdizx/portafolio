<template>
	<v-app>
		<Toolbar />
		<v-main>
			<div id="main">
				<v-card color="secondary darken-2">
					<router-view />
				</v-card>
			</div>
		</v-main>
	</v-app>
</template>

<script lang="ts">
	import Vue from 'vue';
	import Toolbar from '@/components/Toolbar.vue';

	export default Vue.extend({
		name: 'App',
		components: {
			Toolbar,
		},
	});
</script>
