<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title class="ion-text-center">Quizz Corte 3</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <form>
        <ion-item>
          <InputGeneric type="text" id="nombre" name="nombre" label="Nombre:"/></ion-item>
        <ion-item> <InputGeneric type="text" id="fecha" name="fecha" label="Fecha Nacimiento:"/></ion-item>
        <ion-item><InputGeneric id="nombre" name="nombre" label="Celular:"/></ion-item>
        <ion-item> <InputGeneric type="text" id="correo" name="correo" label="Correo Electrónico"/> </ion-item>

        <ion-item>
          <ButtonGeneric id="save" value="Agregar" color="success"/>
          <ButtonGeneric id="delete" value="Eliminar" color="danger"/>
          <ButtonGeneric id="update" value="Modificar" color="warning"/>
          <ButtonGeneric id="consult" value="Consultar"/>
        
        </ion-item>
        <ion-item>
        <OtroGeneric label="Campo Personalizado:"/>
        </ion-item>
        <ion-item>
        <OtroGeneric inputmode=""/>
        </ion-item>
       </form>
    

    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
import InputGeneric from '@/components/InputGeneric.vue';
import ButtonGeneric from '@/components/ButtonGeneric.vue';
import OtroGeneric from '@/components/OtroGeneric.vue'

</script>

<style scoped>
#container {
  text-align: center;
  
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  color: #8c8c8c;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>
