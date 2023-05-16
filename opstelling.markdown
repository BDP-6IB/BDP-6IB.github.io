---
layout: page
title: Opstelling
permalink: /Opstelling/
---

### GitHub Page configuratie

GitHub biedt een service aan genaamd [github actions](https://docs.github.com/en/actions/learn-github-actions). Dit staat toe om arbitraire code te draaien in de cloud. Het kan bijvoorbeeld een linter of een static analyser draaien die de code analyseerd en mogelijke probleemen rapporteerd. GitHub heeft een grote bibliotheek aan actions die al voorgeprogrammeerd zijn. Één van deze actions is een Jekyll page renderen en hosten.

De stappen die nodig zijn om een GitHub page te creëren zijn als volgt:

1.  De naam van de repository moet een bepaald formaat zijn, namelijk "\<organisation>.github.io". ![](\assets\Schermafbeelding 2023-05-12 135913.png)

2. Vervolgens stelt u de bron optie naar GitHub Actions. ![](\assets\Schermafbeelding 2023-05-12 140645.png)

3. Als je op de Visit Site knop klikt, wordt de website geopend.

### Post & Pages
Jekyll heeft 2 mechanismes om een webpagina te maken: Pages en Posts. Allebei zijn markdown bestanden, maar een post heeft een datum van publicatie en zit in /repository/_post. Voor de rest zijn posts en pages gelijk. Wij hebben gekozen om het grootste deel van de inhoudelijk thema's als post te gebruiken. Met enkele algemene thema's, zoals de opstelling, contacten en de home page tot pagina te maken. 

Ieder markdown bestand begint met een [Front Matter](https://jekyllrb.com/docs/front-matter/), die de configuratie bepaalt van de markdown.

> \-\-\-
> 
> layout: page
> 
> title: Opstelling
> 
> permalink: /Opstelling/
> 
> \-\-\-

Hier een overzicht van enkele variabelen en hun betekenis:

| Variable | Betekenis|
| -------- | -------- |
| layout | Is dit een post of een page |
| title | Wat is de titel |
| Permalink | De link waar de post/page gevonden kan worden |
| Published | Is de page/post zichtbaar |

### Samenwerking

We probeerden vanaf dag 1 de taken eerlijk te verdelen en omdat Sander hier goed in was, maakte hij de pages + branches aan. De rest zou deze dan ontwikkelen en hier info indien nodig invullen. Iedereen kon aan elkaar vragen stellen en helpen.

