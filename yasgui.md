---
layout: default
title: SPARQL
---
<div id='sparql-editor'></div>
<script>
YASGUI.YASQE.defaults.value = 'SELECT * WHERE {\n ?s ?p ?o .\n} \nLIMIT 10';
YASGUI.defaults.yasqe.sparql.endpoint = 'https://data.labs.pdok.nl/sparql';
YASGUI.YASR.plugins.leaflet.defaults.defaultMap = "nlmaps";
const yasgui = YASGUI(document.getElementById('sparql-editor'));
</script>
