<template>
	<div>
		<v-card class="mx-auto">
			<v-card color="secondary darken-2">
				<v-card-title>{{ titulo }}</v-card-title>
				<v-card-subtitle>
					<v-expansion-panels>
						<v-expansion-panel>
							<v-expansion-panel-header>
								Descripción
							</v-expansion-panel-header>
							<v-expansion-panel-content>{{ subTitulo }}</v-expansion-panel-content>
						</v-expansion-panel>
					</v-expansion-panels>
				</v-card-subtitle>
			</v-card>

			<v-card color="secondary darken-1">
				<v-card-text>
					<v-btn color="success" text role="link" :href="pagina" target="_blank">
						Página
						<v-icon>mdi-web</v-icon>
					</v-btn>
					<v-spacer></v-spacer>
					<v-btn color="primary" text role="link" :href="repositorio" target="_blank">
						Repositorio
						<v-icon>mdi-source-repository</v-icon>
					</v-btn>
				</v-card-text>
			</v-card>
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
