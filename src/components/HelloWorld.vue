<script setup>
// Tu peux ajouter des scripts ici si tu as besoin de manipuler plus de logique avec Vue
</script>

<template>
  <section>Construire une safe place pour votre bibliothèque</section>
  <p>
    Comment construire un espace sûr en bibliothèque ?
    Après la déferlante numérique, nous avons créé le concept de « troisième lieu » pour répondre à ces nouvelles pratiques. 
    Suite à la vague #MeToo, les bibliothèques ont commencé à construire des espaces sûrs (safe spaces), où le harcèlement, le harcèlement sexuel et le cyberharcèlement 
    sont combattus grâce à une éducation entre pairs et à l’application d’un protocole adapté. </p>
  
  <!-- Ajouter un lien pour déclencher le téléchargement -->
  <a href="/Protocole_Safe_Place.pdf" download="Protocole_Safe_Place.pdf">
    <button>Télécharger le protocole</button>
  </a> 

  <br>
  <p>Participez ! Envoyer un mail à safebiblio@gmail.com</p>
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
  align-content: justify;
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

