<template>
	<div>
		<v-toolbar dark prominent src="../assets/toolbar_fondo.jpg">
			<v-toolbar-title>
				Bienvenidos a mi perfil
			</v-toolbar-title>

			<v-spacer />

			<v-btn icon>
				<v-icon>mdi-github</v-icon>
			</v-btn>
			<v-btn icon>
				<v-icon>mdi-linkedin</v-icon>
			</v-btn>
			<v-btn icon>
				<v-icon>mdi-instagram</v-icon>
			</v-btn>
			<v-btn icon>
				<v-icon>mdi-file-document</v-icon>
			</v-btn>
		</v-toolbar>
	</div>
</template>

<script>
	export default {
		name: 'Toolbar',
	};
</script>
