---
layout: post
title: Notes de novembre
redirect_from: "/2018/11/21/notes-de-novembre-2018/"
permalink: notes-de-novembre-2018
---

Quelques notes et liens de novembre 2018.

---

# Couplages probabilistes sur «Images de maths»

Le site *[Images des maths](http://images.math.cnrs.fr)* du CNRS (que j'avais 
évoqué [ici](https://semidoc.github.io/mags)) publie, entre autres, des 
articles de vulgarisation de niveau universitaire, et cette fois c'est sur la 
notion de couplage en probabilité. 
Ça tombe bien, je voulais justement en apprendre plus sur 
le sujet, après un exposé de 
[Manuela Fischer](http://people.inf.ethz.ch/fiscmanu/) qui 
utilisait allègrement ce concept 
([ce papier](http://drops.dagstuhl.de/opus/volltexte/2018/9815/pdf/LIPIcs-DISC-2018-26.pdf)
présenté à la conférence [DISC](http://www.disc-conference.org/wp/disc2018/)).


# Environnement «description» en latex

Ce n'est pas nouveau mais c'est peu connu et bien utile : en plus de *itemize* et
*enumerate*, latex possède un troisième type de liste, *description*. 
Ce mode est utile lorsque les choses à lister n'ont pas d'ordre défini, mais des 
titres. On peut aussi utiliser *itemize* en forçant les noms de items, mais le 
rendu est moins bon. Voir [cet article de texblog](https://texblog.org/2008/10/16/lists-enumerate-itemize-description-and-how-to-change-them/) 
pour un exemple. 


# Série de séminaires «Graph Theory in Paris»

Une [série de séminaires de graphes](https://www.irif.fr/gtp/index) commence 
le 23 novembre.
Le but (louable) est de rassembler la communauté graphes d'Île-de-France.


# Carte de la théorie du calcul distribué 

[Jukka Suomela](https://users.ics.aalto.fi/suomela/) a publié 
[une carte](https://plus.google.com/+JukkaSuomela/posts/JgWYFk4XzWW) très lisible 
de la communauté PODC/DISC (théorie du calcul distribué) en faisant des liens entre 
les chercheurs qui ont été co-auteurs plusieurs fois, ou dont les travaux ont été
présentés plusieurs fois dans la même session. Sans surprise il y a plusieurs
clusters assez séparés.

 
# Modélisation d’incertitudes

J'ai assisté à un exposé de 
[Nicolas Bousquet](http://www.lsta.upmc.fr/bousquet/) à propos de 
modélisation, de probabilités et d'épistémologie. En gros la question était : 
est-il bien raisonnable de modéliser toutes les incertitudes par des 
probabilités? Deux éléments que j'ai retenus: 

* Si on définit une théorie de la *plausibilité*, en mettant des règles naturelles
pour ce qui est plus ou moins plausible en fonction des données etc. on retombe 
généralement sur une théorie «isomorphe» à celle des probabilités, par le 
[théorème de Cox-Jaynes](https://fr.wikipedia.org/wiki/Th%C3%A9or%C3%A8me_de_Cox-Jaynes).
* On peut utiliser la 
[complexité de Kolmogorov](https://fr.wikipedia.org/wiki/Complexit%C3%A9_de_Kolmogorov) 
pour justifier l'emploi de probabilités en modélisation. Si une suite de valeurs 
d'erreurs ne peut pas être compressées alors elle est en quelque sorte 
aléatoire. L'exposé évoquait aussi l'indécidabilité de certaines propriétés.


# «Nouvelles» fonctionnalités pour arXiv et DBLP

Je n'ai réalisé que récemment que [Arxiv](https://arxiv.org/) et 
[DBLP](https://dblp.uni-trier.de/) faisaient plus que ce que je ne 
pensais ; évitant une partie des aller-retours pénibles sur google scholar. 

* arXiv fait des liens vers les articles cités et vers les articles citant le 
papier que l'on regarde. (Voir par exemple la [page](https://arxiv.org/abs/1802.06676)
de l'article cité plus haut qui utilise les couplages probabilistes). 
* DBLP permet la recherche d'articles par leurs titres (et non seulement la 
recherche d'auteurs).



