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
				sub-titulo="Solamente almacena información no tiene que mostrar ninguna vista.
				Aplicación que permite registrar inventarios, realizar ventas, obtener un listado de facturas
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
				sub-titulo="Este proyecto era una simulación para probar la efectividad que
				 podría tener una herramienta digital para mantener un control y registro
				  de las personas de la Universidad Mariana respecto a su situación frente
				   al COVID-19, genera gráficas de resumen y categoriza la información por
				    roles o cargos desempeñados en la Universidad y también por facultad
				     a la que pertenecen estas personas. ANGULAR - JAVASCRIPT"
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
				sub-titulo="Solamente almacena información no tiene que mostrar ninguna vista.
				Este proyecto era una simulación para probar la efectividad que
				 podría tener una herramienta digital para mantener un control y registro
				  de las personas de la Universidad Mariana respecto a su situación frente
				   al COVID-19, genera gráficas de resumen y categoriza la información por
				    roles o cargos desempeñados en la Universidad y también por facultad
				     a la que pertenecen estas personas. JAVA - SPRING"
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
				sub-titulo="Aplicación genérica que permite llevar el control de las ventas de los
				 productos de cualquier establecimiento comercial, fue creado inicialmente para
				  un restaurante del municipio de Consacá Nariño. Las funcionalidades que tiene
				   son de registros y listado de ventas y productos para los establecimientos
				    comerciales que lo requieran. VUE - JAVASCRIPT"
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
				sub-titulo="Aplicación creada con fines académicos para probar las peticiones a
				 un Api que contiene la información de los países del mundo y conectarlas por
				  medio de protocolo http y sus diferentes métodos. JAVASCRIPT - ANGULAR"
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
