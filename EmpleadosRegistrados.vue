<template>
  <div class="container is-fullhd">
    <div class="card">
      <h3>Empleados Registrados</h3>
      <div class="table-container">
        <table class="table is-striped is-fullwidth">
          <thead>
            <th>#</th>
            <th>Nombres</th>
            <th>Apellidos</th>
            <th>Codigo</th>
            <th>*</th>
          </thead>
          <tbody>
            <tr v-for="index in 10" :key="index">
              <td>{{ index }}</td>
              <td>Flor De Maria</td>
              <td>Cantara Flores</td>
              <td>IN1001</td>
              <td>
                <button class="button is-info is-light">Ver</button>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <div class="card">
      <h4>Detalle Empleados</h4>
      <div class="box">
        <article class="media">
          <div class="media-left">
            <figure class="image is-64x64">
              <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
            </figure>
          </div>
          <div class="media-content">
            <div class="content">
              <p>
                <strong>Nombres: </strong> <span>Flor De Maria</span>
              </p>
              <p>
                <strong>Apellidos: </strong> <span>Cantara Flores</span>
              </p>
              <p>
                <strong>Edad: </strong> <span>28 años</span>
              </p>
              <p>
                <strong>DNI: </strong> <span>12345678</span>
              </p>
              <p>
                <strong>Codigo: </strong> <span>IN1001</span>
              </p>
              <p>
                <strong>Area: </strong> <span>Informatica</span>
              </p>
            </div>
          </div>
        </article>
      </div>
    </div>
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
