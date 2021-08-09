<template>
	<div>
		<v-carousel>
			<v-carousel-item
				v-for="(imagen, i) in imagenes"
				:key="i"
				:src="getImgUrl(imagen.src)"
				reverse-transition="fade-transition"
				transition="fade-transition"
			>
			</v-carousel-item>
		</v-carousel>
	</div>
</template>

<script>
	export default {
		name: 'Certificados',
		data() {
			return {
				imagenes: [{ src: 'GCP' }, { src: '14CCC' }, { src: 'CACIED4' }, { src: 'CIC' }],
			};
		},
		methods: {
			getImgUrl(pet) {
				const images = require.context('../assets/certificados/', false, /\.jpg$/);
				return images('./' + pet + '.jpg');
			},
		},
	};
</script>
