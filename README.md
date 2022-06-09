# vue-dc-comics

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

Ciao ragazzi,
Esercizio di oggi: Vue DC Comics
nome repo: vue-dc-comics
Descrizione:

Create un nuovo progetto utilizzando Vue CLI 
<!-- OK -->

Definite i componenti necessari per strutturare il layout come da screenshot allegato.
<!-- OK -->

Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.
<!-- OK -->

Per oggi diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass! (cioè ai dettagli del layout)
<!-- OK -->

Bonus:
Creare un componente aggiuntivo per gestire la fascia azzurra con le icone.
<!-- OK -->
+ altri di cui abbiam parlato.

Se volete caricare le immagini salvate in assets in maniera dinamica dai data() di Vue, dovrete utilizzare il require()

Quindi se avete una immagine caricata in questo modo nei data:

img: "../assets/img/buy-dc-power-visa.svg"

dovrete aggiungere il require:

img: require("../assets/img/buy-dc-power-visa.svg")

in pratica se non vi appaiono le immagini provate col require