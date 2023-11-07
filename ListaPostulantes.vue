<template>
  <div class="column">
    <h3>Lista de Postulantes</h3>
    <table class="table">
      <thead>
        <th>DNI</th>
        <th>Nombres</th>
        <th>Edad</th>
        <th>Accion</th>
      </thead>
      <tbody>
        <tr v-for="index in 10" :key="index">
          <td>{{ index }}</td>
          <td>{{ index }}  nombres</td>
          <td>{{ index }} años</td>
          <td>
            <div class="buttons">
              <button class="button is-warning">Aprobar</button>
              <button class="button is-danger">Rechazar</button>
            </div>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  setup () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>
