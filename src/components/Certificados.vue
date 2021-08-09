<template>
	<v-carousel>
		<v-carousel-item
			v-for="(imh, i) in imagenes"
			:key="i"
			:src="imh.src"
			reverse-transition="fade-transition"
			transition="fade-transition"
		>
		</v-carousel-item>
	</v-carousel>
</template>

<script>
	export default {
		name: 'Certificados',
		data() {
			return {
				imagenes: [
					{
						src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg',
					},
					{
						src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
					},
					{
						src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
					},
					{
						src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
					},
				],
			};
		},
	};
</script>
