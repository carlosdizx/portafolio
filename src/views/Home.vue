<template>
	<Toolbar />
</template>

<script lang="ts">
	import Vue from 'vue';
	import Toolbar from '@/components/Toolbar.vue';

	export default Vue.extend({
		name: 'Home',

		components: { Toolbar },
	});
</script>
