<template>

    <ion-page>
        <ion-header>
        <ion-toolbar color="success">
            <ion-title>Login</ion-title>
        </ion-toolbar>
        </ion-header>

        <ion-content>
                <ion-item>
                    <ion-label position="floating">Email</ion-label>
                    <ion-input></ion-input>
                </ion-item>
                 <ion-item>
                    <ion-label position="floating">Password</ion-label>
                    <ion-input type="password"></ion-input>
                </ion-item>
                <ion-button expand="block" color="danger">Login</ion-button>
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
    IonItem,
    IonLabel,
    IonInput
} from'@ionic/vue'
import{defineComponent} from 'vue'

export default defineComponent({
    components:{
    IonPage,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonItem,
    IonLabel,
    IonInput
    }
})

</script>

<style scoped>

</style>

