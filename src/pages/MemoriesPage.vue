<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>All Memories</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
        <ion-item>Playing Hockey</ion-item>
        <ion-item>Playing Soccer</ion-item>
        <ion-item>Fighting Bulls</ion-item>
        <ion-item>San Fransisco</ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
  IonList,
  IonItem,
} from "@ionic/vue";

export default {
  components: {
    IonPage,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonList,
    IonItem,
  },
};
</script>
