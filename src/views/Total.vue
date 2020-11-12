<template>
  <div>
    <h1 class="display-5 text-center my-4">Total</h1>
    <hr>
    <div class="container py-3">
      <h2>Listado de ventas registradas</h2>
      <tabla-ventas></tabla-ventas>
    </div>
    <hr>
    <div class="container py-3">
      <h2>Monto total de ventas</h2>
      <h5>$ {{totalVentas}}</h5>
    </div>
  </div>
</template>

<script>
import TablaVentas from '../components/TablaVentas.vue'
import { mapGetters } from "vuex";

export default {
  name: 'Total',
  components: {
    TablaVentas
  },
  computed: {
    ...mapGetters(['totalVentas'])
  },
}
</script>