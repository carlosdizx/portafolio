<template>
	<div>
		<v-card class="mx-auto">
			<v-card-title>{{ titulo }}</v-card-title>
			<v-card-subtitle>
				<v-expansion-panels>
					<v-expansion-panel>
						<v-expansion-panel-header>
							Descripción
						</v-expansion-panel-header>
						<v-expansion-panel-content>{{ subTitulo }}</v-expansion-panel-content>
					</v-expansion-panel>
				</v-expansion-panels></v-card-subtitle
			>
			<v-card-text>
				<v-btn color="success" text>
					Pagina
					<v-icon>mdi-web</v-icon>
				</v-btn>
				<v-spacer></v-spacer>
				<v-btn color="primary" text>
					Repositorio
					<v-icon>mdi-source-repository</v-icon>
				</v-btn>
			</v-card-text>
		</v-card>
	</div>
</template>

<script>
	export default {
		name: 'Proyecto',
		components: {},
		props: {
			titulo: String,
			subTitulo: String,
			pagina: String,
			repositorio: String,
		},
	};
</script>

<style scoped></style>
