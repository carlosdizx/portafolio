<template>
	<v-container>
		<v-card-title class="text-h5 text--white">
			Proyectos
		</v-card-title>
		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img1.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Inventas-Frontend"
				sub-titulo="Aplicación que permite registrar inventarios, realizar ventas, obtener un listado de facturas
					y productos/servicios no vendidos, registrar productos o servicios, registrar clientes y generar informes
					de ventas, productos más vendidos, clientes con más compras. Además, la aplicación cuenta con seguridad y
					 autentificación por roles para los recursos disponibles. VUE - JAVASCRIPT"
				pagina="https://inventas.netlify.app/"
				repositorio="https://github.com/carlosdizx/inventas-frontend"
				advertencia
			/>
		</v-card>

		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img4.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Inventas-Backend"
				sub-titulo="Aplicación que permite registrar inventarios, realizar ventas, obtener un listado de facturas
					y productos/servicios no vendidos, registrar productos o servicios, registrar clientes y generar informes
					de ventas, productos más vendidos, clientes con más compras. Además, la aplicación cuenta con seguridad y
					 autentificación por roles para los recursos disponibles. JAVA - SPRING"
				pagina="https://inventas.herokuapp.com/"
				repositorio="https://github.com/carlosdizx/inventas-backend"
				advertencia
			/>
		</v-card>

		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img2.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Trazabilidad de la situación del COVID19 en la Universidad Mariana - Frontend"
				sub-titulo="Este proyecto era una simulación para probar la efectiva podría tener una herramienta digital para
					 mantener un control y registro de las personas de la Universidad Mariana
					 respecto a su situación frente al COVID-19, genera gráficas de resumen y categoriza
					  la información por roles o cargos desempeñados en la
					  Universidad y también por facultad a la que pertenecen estas personas. ANGULAR - JAVASCRIPT"
				pagina="https://umariana-traza-covid19.netlify.app/"
				repositorio="https://github.com/carlosdizx/VacunacionCovid19UniversidadMarianaFrontend"
				advertencia
			/>
		</v-card>

		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img5.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Trazabilidad de la situación del COVID19 en la Universidad Mariana - Backend"
				sub-titulo="Este proyecto era una simulación para probar la efectiva podría tener una herramienta digital para
					 mantener un control y registro de las personas de la Universidad Mariana
					 respecto a su situación frente al COVID-19, genera gráficas de resumen y categoriza
					  la información por roles o cargos desempeñados en la
					  Universidad y también por facultad a la que pertenecen estas personas. JAVA - SPRING"
				pagina="https://traza-mariana.herokuapp.com/"
				repositorio="https://github.com/carlosdizx/Vacunacion-Universidad-Mariana-Covid19"
				advertencia
			/>
		</v-card>

		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img3.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Caja registradora"
				sub-titulo="Aplicación para llevar registro de ventas de un restaurante del municipio de Consacá Nariño VUE - JAVASCRIPT"
				pagina="https://caja-registradora.netlify.app/"
				repositorio="https://github.com/carlosdizx/caja-registradora"
			/>
		</v-card>

		<v-card class="mt-12">
			<v-container>
				<v-card-title>
					<v-img src="../assets/proyectos/img6.png" />
				</v-card-title>
			</v-container>
			<Proyecto
				titulo="Paises del mundo"
				sub-titulo="Muestra el listado de países del mundo, los agrupa por diferentes
				 como son por regiones, además de que tiene por cada país datos únicos de este. ANGULAR - JAVASCRIPT"
				pagina="https://arena-paises-del-mundo.netlify.app/"
				repositorio="https://github.com/carlosdizx/Paises-del-Mundo"
			/>
		</v-card>
	</v-container>
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
