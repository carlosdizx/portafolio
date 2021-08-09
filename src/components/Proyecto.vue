<template>
  <div>
    <v-card class="mx-auto">
      <v-card-title>{{ titulo }}</v-card-title>
      <v-card-subtitle>{{ subTitulo }}</v-card-subtitle>
      <v-card-actions>
        <v-btn color="success" text> Pagina
          <v-icon>mdi-web</v-icon>
        </v-btn>
        <v-spacer/>
        <v-btn color="primary" text>
          Repositorio
          <v-icon>mdi-source-repository</v-icon>
        </v-btn>
      </v-card-actions>
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
