<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <ion-grid>
        <ion-row class="justify-content-center">
          <ion-col class="height-50"></ion-col>
          <ion-col size="12" class="ion-margin-top-human">
            <h3 class="ion-color-primary ion-text-center">HUMAN</h3>
          </ion-col>
          <ion-col size="12" class="ion-text-center">
            <ion-button class="ion-margin">
              Sign Up
            </ion-button>
            <ion-button class="ion-margin">
              Sign In
            </ion-button>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonContent, IonPage } from '@ionic/vue';
import { defineComponent } from 'vue'; 

export default defineComponent({
  name: 'Home',
  components: {
    IonContent,
    IonPage,
  }
});
</script>

<style scoped>
.height-50{
  height: 50vh;
}
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