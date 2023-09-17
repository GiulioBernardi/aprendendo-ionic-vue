<template>
    <base-layout page-title="All Memories">
        <ion-list>
            <ion-item router-link="/memories/1">Festa de 21 anos</ion-item>
            <ion-item router-link="/memories/2">Aniversário Bisi</ion-item>
            <ion-item router-link="/memories/3">Sangava</ion-item>
        </ion-list>
    </base-layout>
</template>

<script>
import { IonList, IonItem } from '@ionic/vue'
import BaseLayout from '../components/base/BaseLayout.vue'
export default {
    components:{
        IonList,
        IonItem
    }
}
</script>

        BaseLayout
<style scoped>

</style>
