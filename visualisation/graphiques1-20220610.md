---
layout: post
title: Demandes d'asile et accords - France
parent : VISU
nav_order: 1

---

# Premières demandes d’asile et accords en France (2001-2019)

<script>
  const password = prompt("Veuillez entrer le mot de passe pour accéder à cette page:");
  if (password !== "motdepassedatasile") {
    alert("Mot de passe incorrect !");
    window.location.href = "https://datasile.org/visualisation/graphiques1-20220610.html"; // Redirection si le mot de passe est incorrect
  }
</script>

<div id="graph1">
  <div class="introduction1"></div>
  <div class="viewof-dataG" style="margin-bottom: 0.5em"></div>
  <div class="graphique1"></div>
  <div class="legende1"></div>
</div>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/d/65fe5202d85f33e2.js?v=3";
new Runtime().module(define, name => {
  if (name === "introduction1") return new Inspector(document.querySelector("#graph1 .introduction1"));
  if (name === "graphique1") return new Inspector(document.querySelector("#graph1 .graphique1"));
  if (name === "viewof dataG") return new Inspector(document.querySelector("#graph1 .viewof-dataG"));
  if (name === "legende1") return new Inspector(document.querySelector("#graph1 .legende1"));
});
</script>
