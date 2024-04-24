
<template>
    <ion-item>
      <ion-label>{{ label }}</ion-label>
      <ion-input v-bind="$attrs" :type="type" :id="id" :value="value" :placeholder="placeholder" :clearInput="clearInput" :debounce="debounce" :disabled="disabled" :maxlength="maxlength" :min="min" :max="max" :step="step"></ion-input>
     </ion-item>
  </template>
  
  <script lang="ts">
  import { IonInput, IonLabel } from '@ionic/vue';
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    components: { IonLabel, IonInput },
    props: {
        label: {
            type: String,
            required: false
         },
   
      name: String,
      expand: String,
      color: String,
      size: String,
      fill: String,
      shape: String,
      disabled: Boolean,
      type: String,
      href: String
    }
  });
  </script>
  
  <style scoped>
    /* Estilo global */
  </style>
  
  