<template>
  <div class="content">
    <h1>Registrar postulante</h1>
    <div>
      <div class="field">
        <label class="label">DNI</label>
        <div class="control">
          <input class="input" type="text" placeholder="Text input">
        </div>
      </div>
      <div class="field">
        <label class="label">Nombres</label>
        <div class="control">
          <input class="input" type="text" placeholder="Text input">
        </div>
      </div>
      <div class="field">
        <label class="label">Apellidos</label>
        <div class="control">
          <input class="input" type="text" placeholder="Text input">
        </div>
      </div>
      <div class="field">
        <label class="label">F. Nacimiento</label>
        <div class="control">
          <input class="input" type="date" placeholder="Text input">
        </div>
      </div>
    </div>
    <br>
    <div class="buttons">
      <button class="button is-primary">Guardar</button>
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
