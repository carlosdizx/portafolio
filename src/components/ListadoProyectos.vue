<template>
	<div>
		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img1.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Inventas"
				sub-titulo="Aplicación que permite registrar inventarios, realizar ventas, obtener un listado de facturas
					y productos/servicios no vendidos, registrar productos o servicios, registrar clientes y generar informes
					de ventas, productos más vendidos, clientes con más compras. Además, la aplicación cuenta con seguridad y
					 autentificación por roles para los recursos disponibles."
			/>
		</v-card>
		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img2.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Trazabilidad de la situación del COVID19 en la Universidad Mariana"
				sub-titulo="Este proyecto era una simulación para probar la efectiva podría tener una herramienta digital para
					 mantener un control y registro de las personas de la Universidad Mariana
					 respecto a su situación frente al COVID-19, genera gráficas de resumen y categoriza
					  la información por roles o cargos desempeñados en la
					  Universidad y también por facultad a la que pertenecen estas personas."
			/>
		</v-card>
	</div>
</template>

<script>
	import Proyecto from './Proyecto';
	export default {
		name: 'ListadoProyectos',
		components: {
			Proyecto,
		},
	};
</script>

<style scoped></style>
