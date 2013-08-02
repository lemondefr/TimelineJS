# TimelineJS et Le Monde.fr 

Le Monde.fr utilise TimelineJS régulièrement pour proposer à ses lecteurs
un retour sur les feuilleton d'actualité les plus importants. Depuis la 
[première utilisation](http://www.lemonde.fr/election-presidentielle-2012/visuel/2012/04/21/chronologie-une-si-longue-campagne-presidentielle_1681661_1471069.html)

Ce *repositorie* permet de garder une version customisée pour Le Monde.fr de 
ces chronologies.
 
```
### Initialisation

Prendre le projet "compiled" et modifier le titre de l'article, ainsi que la clé 
du document Google Doc. Ce document doit être publié pour le web.

N'hésitez pas à utiliser du html dans le Google Doc et notamment la classe "lire" 
pour les liens "Lire aussi".

Ces liens peuvent être écrits sous la forme : 

```html
<p class="lire">Lire : <a href="xxx" target="_blank">Titre du lien</a></p>

###Start at End 
`start_at_end`
set to true to start the timeline on the last date.
*default is false*

###Start at Slide 
`start_at_slide`
You can tell TimelineJS to start at a specific slide number
*default is 0*

## License
This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, You can obtain one at http://mozilla.org/MPL/2.0/.


