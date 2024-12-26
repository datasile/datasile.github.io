---
layout: default
nav_order : 2
title : Dublin Visu
nav_exclude: true
has_children: true
--- 
<div id="observablehq-TitleContent-9500aee6"></div>
<div id="observablehq-text2-9500aee6"></div>
<div id="observablehq-text22-9500aee6"></div>
<div id="observablehq-text4-9500aee6"></div>
<div id="observablehq-text5-9500aee6"></div>
<p>Credit: <a href="https://observablehq.com/d/14be36dab42d4754">What is this Page? by datasile</a></p>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
import define from "https://api.observablehq.com/d/14be36dab42d4754.js?v=4";
new Runtime().module(define, name => {
  if (name === "TitleContent") return new Inspector(document.querySelector("#observablehq-TitleContent-9500aee6"));
  if (name === "text2") return new Inspector(document.querySelector("#observablehq-text2-9500aee6"));
  if (name === "text22") return new Inspector(document.querySelector("#observablehq-text22-9500aee6"));
  if (name === "text4") return new Inspector(document.querySelector("#observablehq-text4-9500aee6"));
  if (name === "text5") return new Inspector(document.querySelector("#observablehq-text5-9500aee6"));
});
</script>
