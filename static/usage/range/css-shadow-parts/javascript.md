```html
<ion-app>
  <ion-content class="ion-padding">
    <ion-range min="0" max="10" value="5" pin="true" ticks="true" snaps="true"></ion-range>
  </ion-content>
</ion-app>

<style>
  ion-range::part(tick) {
    background: #a2d2ff;
  }

  ion-range::part(tick-active) {
    background: #bde0fe;
  }

  ion-range::part(pin) {
    display: inline-flex;
    align-items: center;
    justify-content: center;

    background: #ffafcc;
    color: #fff;

    border-radius: 50%;
    transform: scale(1.01);

    top: -20px;

    min-width: 28px;
    height: 28px;
    transition: transform 120ms ease, background 120ms ease;
  }

  ion-range::part(pin)::before {
    content: none;
  }

  ion-range::part(knob) {
    background: #ffc8dd;
  }

  ion-range::part(bar) {
    background: #a2d2ff;
  }

  ion-range::par(bar-active) {
    background: #bde0fe;
  }
</style>
```
