---
layout: post
title: Techniques d'embed
hidden: true
nav_exclude: true
search_exclude: true
---

# Techniques d'embed

## iframe

<iframe width="100%" height="676" frameborder="0"
  src="https://observablehq.com/embed/@bert/terrains-with-maplibre?cells=viewof+map"></iframe>

<div style="margin-bottom: 5em"></div>

----

## javascript

<div id="observablehq-chart-ea65d5fc"></div>
<div id="observablehq-viewof-replay-ea65d5fc"></div>
<div id="observablehq-viewof-steps-ea65d5fc"></div>
<div id="observablehq-viewof-ticks-ea65d5fc"></div>
<div id="observablehq-addlabel-ea65d5fc"></div>

<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/@fil/tricontour-labels.js?v=3";
new Runtime().module(define, name => {
  if (name === "chart") return new Inspector(document.querySelector("#observablehq-chart-ea65d5fc"));
  if (name === "viewof replay") return new Inspector(document.querySelector("#observablehq-viewof-replay-ea65d5fc"));
  if (name === "viewof steps") return new Inspector(document.querySelector("#observablehq-viewof-steps-ea65d5fc"));
  if (name === "viewof ticks") return new Inspector(document.querySelector("#observablehq-viewof-ticks-ea65d5fc"));
  // if (name === "addlabel") return new Inspector(document.querySelector("#observablehq-addlabel-ea65d5fc"));
  return ["data","color","thresholds"].includes(name);
});
</script>
