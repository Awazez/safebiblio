<script setup>
// Tu peux ajouter des scripts ici si tu as besoin de manipuler plus de logique avec Vue
</script>

<template>
  <section>Construire une safe place pour votre bibliothèque</section>
  
  <!-- Ajouter un lien pour déclencher le téléchargement -->
  <a href="/public/Protocole_Safe_Place.pdf" download="Protocole_Safe_Place.pdf">
    <button>Télécharger le protocole</button>
  </a> 
  
  <br>
  <p>Participez ! Envoyer un mail à contact@safebiblio.fr</p>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');

section {
  font-size: 3em;
  font-family: "Montserrat", system-ui;
  font-weight: 900;
  font-style: bold italic;
  color: black;
}

p {
  font-family: "Montserrat", system-ui;
  font-weight: 900;
  color: black;
}

button {
  background: white;
  color: black;
  border: none;
  padding: 10px 20px;
  font-family: "Montserrat", system-ui;
  font-weight: 700;
  cursor: pointer;
}

button:hover {
  background-color: #000;
  color: #fff;
}
</style>

