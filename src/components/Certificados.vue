<template>
	<div>
		<v-carousel cycle>
			<v-carousel-item
				reverse-transition="fade-transition"
				transition="fade-transition"
				v-for="(imagen, i) in imagenes"
				:key="i"
			>
				<v-img contain class="fill-height" :src="darRutaImagen(imagen.src)"> </v-img>
			</v-carousel-item>
		</v-carousel>
	</div>
</template>

<script>
	export default {
		name: 'Certificados',
		data() {
			return {
				imagenes: [
					{ src: 'GCP' },
					{ src: 'UD_ANGULAR_SPRING' },
					{ src: 'PRO_FUTURO_HTML_JS' },
					{ src: '14CCC' },
					{ src: 'CACIED4' },
					{ src: 'CIC' },
				],
			};
		},
		methods: {
			darRutaImagen(pet) {
				const images = require.context('../assets/certificados/', false, /\.jpg$/);
				console.log(images('./' + pet + '.jpg'));
				return images('./' + pet + '.jpg');
			},
		},
	};
</script>
