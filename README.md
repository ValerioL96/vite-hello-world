# Vue 3 + Vite
Descrizione:

Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!"

1) creo un componente AppTitle;
2) aggiungo in template del componente Apptitle un h1 con scritto "La mia prima app con Vite!":

- < template>
< h1>La mia prima app con Vite!< /h1>
< /template>

3) importo in App.vue il componente AppTitle:

- < script setup>
import AppTitle from './components/AppTitle.vue'
< /script>
