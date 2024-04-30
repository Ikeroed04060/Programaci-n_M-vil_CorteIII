<template>
    <ion-page>
      <ion-header :translucent="true">
        <ion-toolbar>
          <ion-title>Carrito de compra</ion-title>
        </ion-toolbar>
      </ion-header>  
      <ion-content>       
        <div id="login-container">  
          <div id="login-form">
            <PersonaComponent/>
            <InputComponent id="direccion" name="direccion" label="Dirección: " />
            <InputComponent id="metodoPago" name="metodoPago" label="Método Pago: " />            
          </div>
  
          <div> 
             <!--Traer el componente de los botones de la crud  -->
            <CrudButtonComponent />
          </div>          
        </div>
      </ion-content>
    </ion-page>
  </template>
  
  <script setup lang="ts">
  import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';

  import InputComponent from '@/components/InputComponent.vue';
  import CrudButtonComponent from '@/components/CrudButtonComponent.vue';
import PersonaComponent from '@/components/PersonaComponent.vue';
  </script>
  
  <style scoped src="../theme/container.css"></style>

