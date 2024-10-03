<template>
  <div class="body">
    <CarnetComponent
      RUN="12.345.678-9"
      apellidos="Pérez González"
      nombres="Juan Andrés"
      nacionalidad="Chilena"
      sexo="Masculino"
      fechaNacimiento="1990-05-12"
      fechaEmision="2022-10-01"
      fechaVencimiento="2032-10-01"
      numeroDocumento="AB123456789"
    />
  </div>
</template>

<script>
import CarnetComponent from './components/CarnetComponent.vue';
export default {
  name: 'App',
  components: {
    CarnetComponent
  }
}
</script>

<style>
 .body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 60vh;
        font-size: 10px;
        font-family: sans-serif;
      }
</style>
