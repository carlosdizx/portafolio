<template>
	<v-card dark>
		<v-card-title>
			Carlos Ernesto Díaz Basante
		</v-card-title>
		<v-card-subtitle>
			Ingeniero de Sistemas - Universidad Mariana
		</v-card-subtitle>
		<v-card-text>
			<v-container>
				<div>
					Hola
				</div>
			</v-container>
		</v-card-text>
	</v-card>
</template>

<script>
	export default {
		name: 'Info',
	};
</script>

<style scoped>
	div {
		min-height: 0;
		background-image: url('../assets/foto_perfil.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
		background-attachment: fixed;
	}

	div:before {
		content: '';
		width: 100%;
		min-height: 100%;
		position: absolute;
		top: 0;
		left: 0;

		background: linear-gradient(90deg, #52c4df, #ad55c1);
		opacity: 0.15;
	}
</style>
