<template>
  <div class="content">
    <div class="card ">
      <div class="field">
        <label class="label">DNI</label>
        <div class="control">
          <input class="input" type="number" placeholder="DNI">
        </div>
      </div>

      <div class="field">
        <label class="label">Nombres</label>
        <div class="control">
          <input class="input" type="text" placeholder="Nombres">
        </div>
      </div>

      <div class="field">
        <label class="label">Apellidos</label>
        <div class="control">
          <input class="input" type="text" placeholder="Apellidos">
        </div>
      </div>
      <div class="field">
        <label class="label">F. Nacimiento</label>
        <div class="control">
          <input class="input" type="date" placeholder="Nacimiento">
        </div>
      </div>

      <div class="field">
        <label class="label">Area:</label>
        <div class="select">
          <select >
            <option value="Informática">Informática</option>
            <option value="Contabilidad">Contabilidad</option>
            <option value="Administracion">Administracion</option>
            <option value="Caja">Caja</option>
          </select>
        </div>
      </div>

      <div class="field">
        <label class="label">Codigo Empleado</label>
        <div class="control">
          <input class="input" type="text" placeholder="Codigo">
        </div>
      </div>
      <p class="is-primary"> aqui error </p>
      <button class="button is-primary" >Actualizar Datos</button>
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
