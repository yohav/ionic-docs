```html
<template>
  <ion-content>
    <ion-button id="auto-trigger">Size=Auto</ion-button>
    <ion-popover trigger="auto-trigger" size="auto">
      <ion-content class="ion-padding">Hello!</ion-content>
    </ion-popover>

    <ion-button id="cover-trigger">Size=Cover</ion-button>
    <ion-popover trigger="cover-trigger" size="cover">
      <ion-content class="ion-padding">Hello!</ion-content>
    </ion-popover>
  </ion-content>
</template>

<script lang="ts">
  import { IonButton, IonContent, IonPopover } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: { IonButton, IonContent, IonPopover },
  });
</script>
```
