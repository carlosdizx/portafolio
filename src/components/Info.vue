<template>
	<v-card dark>
		<v-card-title>
			Carlos Ernesto Díaz Basante
		</v-card-title>
		<v-card-subtitle class="text-black">
			Ingeniero de Sistemas - Universidad Mariana
		</v-card-subtitle>
		<v-card-text>
			<v-container>
				<v-card class="mx-auto" max-width="700">
					<v-card-title>
						{{ infoBio }}
						<v-spacer />
						Un gusto conocerte 😎✌
						<v-spacer />
						~Carlos Díaz
					</v-card-title>
				</v-card>
			</v-container>
		</v-card-text>
	</v-card>
</template>

<script>
	import { INFO_BIO } from '@/assets/textos';

	export default {
		name: 'Info',
		data: () => ({
			infoBio: INFO_BIO,
		}),
	};
</script>

<style scoped>
	.v-card {
		min-height: 0;
		background-image: url('../assets/foto_perfil.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
		background-attachment: fixed;
		z-index: 1;
	}

	.v-card:before {
		content: '';
		width: 100%;
		min-height: 100%;
		position: absolute;
		top: 0;
		left: 0;

		background: linear-gradient(90deg, #181a1a, #817288);
		opacity: 0.7;
		z-index: -1;
	}
</style>
