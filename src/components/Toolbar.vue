<template>
	<div>
		<v-toolbar dark prominent src="../assets/toolbar_fondo.jpg">
			<v-toolbar-title>
				Bienvenido a mi perfil
			</v-toolbar-title>

			<v-spacer />

			<v-btn icon href="https://github.com/carlosdizx" target="_blank">
				<v-icon>mdi-github</v-icon>
			</v-btn>
			<v-btn icon href="https://www.linkedin.com/in/carlos-ernesto-diaz-basante-2872ab210/" target="_blank">
				<v-icon>mdi-linkedin</v-icon>
			</v-btn>
			<v-btn icon href="https://www.instagram.com/carlosdix98/" target="_blank">
				<v-icon>mdi-instagram</v-icon>
			</v-btn>
			<v-btn icon href="https://drive.google.com/file/d/1WKJJIPNQDPWim68-pb1o8n1oh37L5fYG/view?usp=sharing" target="_blank">
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
