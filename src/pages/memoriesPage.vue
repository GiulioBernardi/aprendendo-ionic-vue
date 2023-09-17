<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>All Memories</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <ion-list>
                <ion-item>Giulio</ion-item>
                <ion-item>Carol</ion-item>
                <ion-item>Hugo</ion-item>
                <ion-item>Wesley</ion-item>
                <ion-item>Lucas</ion-item>
                <ion-item>Paty</ion-item>

            </ion-list>
        </ion-content>
    </ion-page>
</template>

<script>
import { IonList, IonItem, IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue'
export default {
    components:{
        IonList,
        IonItem,
        IonPage,
        IonHeader,
        IonToolbar,
        IonTitle,
        IonContent
    }
}
</script>

<style scoped>

</style>
