<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Dashboard</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content>
      <br>
      <div id="container">
        <strong><a href="/cliente">Ir a Clientes</a></strong>
        <br>
        <strong><a href="/producto">Ir a productos</a></strong>
        <br>
        <strong><a href="/empleado">Ir a empledos</a></strong>
        <br>
        <strong><a href="/estudiante">Ir a estudiantes</a></strong>
        <br>

      </div>

    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
</script>

<style scoped></style>
