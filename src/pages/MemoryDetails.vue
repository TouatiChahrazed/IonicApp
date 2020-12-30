<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>All Memories</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
        <ion-item> Chahrazed </ion-item>
        <ion-item> Marwa </ion-item>
        <ion-item> Sihem </ion-item>
      </ion-list>
    </ion-content>
   </ion-page>
</template>

<script>
import {
  IonPage, 
  IonContent,
  IonToolbar,
  IonHeader,
  IonTitle,
  IonList,
  IonItem
} from '@ionic/vue'
export default {
  components: {
    IonContent,
    IonToolbar,
    IonTitle,
    IonPage,
    IonHeader,
    IonList,
    IonItem
  }

}
</script>
