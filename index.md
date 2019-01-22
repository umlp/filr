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

{% assign puml = "http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/plantuml/plantuml-server/master/src/main/webapp/resource" %}

{{ puml }}

Titre : {{ site.title }}
PUML : {{ site.puml }}

![uncached image](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/plantuml/plantuml-server/master/src/main/webapp/resource/test2diagrams.txt)

![uncached image avec liquid]({{ puml }}/test2diagrams.txt)

![uncached image avec liquid](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/umlp/filr/master/assets/uml/dss.txt)
