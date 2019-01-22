---
layout: archive
title: Sommaire
author_profile: true
---
Version 0.9.2

## Activités
 - [Initialiser le projet](activites/initialiser-projet.html)
 
## Guide de rédaction d'artefacts
 - [Fiche d'initialisation de projet](artefacts/fiche-initialisation-projet.html)

{%- assign puml1 = "![uncached image avec liquid](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/plantuml/plantuml-server/master/src/main/webapp/resource" -%}

{%- assign puml2 = "![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/umlp/filr/master/assets/uml" -%}

### PUML :
 - {{ puml }}


### PUML2 :
 - {{ puml2 }}

### NWO :
 - {{ site.github.repository_nwo }}

{%- assign puml0 = "![uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/" | append site.github.repository_nwo | append "/master/assets/uml" -%}

### PUML0 : 
 - {{ puml0 }}

Titre : {{ site.title }}
PUML : {{ site.puml }}

![uncached image](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/plantuml/plantuml-server/master/src/main/webapp/resource/test2diagrams.txt)

![uncached image avec liquid]({{ puml }}/test2diagrams.txt)

![uncached image avec liquid](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/umlp/filr/master/assets/uml/dss.txt)

{{ puml2 }}/dss.txt)
