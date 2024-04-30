<template>
<InputComponent id="id" name="id" label="ID: " />
<InputComponent id="primerNombre" name="primerNombre" label="Primer Nombre " />
<InputComponent id="segundoNombre" name="segundoNombre" label="Segundo Nombre: " />
<InputComponent id="primerApellido" name="primerApellido" label="Primer Apellido: " />
<InputComponent id="segundoApellido" name="segundoApellido" label="Segundo Apellido: " />
<InputComponent id="documento" name="documento" label="Tipo de documento: " />
<InputComponent id="numeroDocumento" name="numeroDocumento" label="Número de Documento: " />
</template>

<script setup lang="ts">
import InputComponent from './InputComponent.vue';
</script>
