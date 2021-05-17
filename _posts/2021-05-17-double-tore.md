---
layout: post
title: Comment coller un double tore?
redirect_from: "/2021/05/17/double-tore/"
permalink: double-tore
---

Bonjour, j'ai décidé d'orienter ce blog-ci vers la vulgarisation et mon
[blog en anglais](https://discrete-notes.github.io/) vers des thématiques plus
proche de ma recherche.  

J'avais publié ce billet il y a environ un an an anglais, et il était
lié à ma recherche du moment, mais je pense que c'est aussi un joli sujet de
vulgarisation. Il s'agit de faire un peu de topologie (algorithmique), avec
beaucoup de dessins.

--

L'idée est de construire un double tore par collage des bords d'un polygone.
Mais comme les constructions sont à déformation pres, elles ne peuvent pas
vraiment être faites en papier, ou alors en papier élastique !
On va parler de topologie dans la veine du fameux «un donut est une tasse de
café : les deux ont un trou».

Le double tore est la surface à deux trous. Pour le construire on va partir de
l'image suivante qui est appelé de schéma polygonal du double tore.
C'est un octogon dont les arêtes sont colorées et orientées. Il y a exactement
deux arêtes de chaque couleurs.

![](assets/2-torus-1.png){: .center-image width="70%"}

La construction consists à appliquer l'opération suivante : prendre deux arêtes
d'un même couleur, et les coller, tel que les orientations soient cohérentes
(les flèches pointent dans le même sens). Commençons avec les arêtes rouges.

![](assets/2-torus-2.png){: .center-image width="70%"}

Faisons de même avec les arêtes jaunes.

![](assets/2-torus-3.png){: .center-image width="70%"}

À ce stade remarquons que comme l'on va coller toutes les paires d'arêtes,
les huit coins du polygone vont devenir le même point.
Pour faciliter le dessin, on va coller deux de ces coins pour relier le chemin
jaune et le chemin rouge. 

![](assets/2-torus-4.png){: .center-image width="70%"}

On arrive au coeur de la construction. Nous avons deux boucles vertes.
Pour les fusionner, nous allons créer une « poignée », c'est-à-dire une sorte de
pont au-dessus de la surface en construction. Cela crée le premier trou. Notez
que le chemin rouge devient une boucle.    

![](assets/2-torus-5.png){: .center-image width="70%"}

On fait de même avec les boucles bleues.

![](assets/2-torus-6.png){: .center-image width="70%"}

Nous avons maintenant deux poignées, et nous avons fini la construction.
Pour rendre la figure plus lisible, tirons un peu sur la surface.

![](assets/2-torus-7.png){: .center-image width="70%"}

Une chose importante ici est que l'opération de collage est réversible.
Pour revenir à l'octogone de départ, on peut simplement prendre des ciseaux
et découper le long des quatre boucle. 

Un théorème général (le théorème de classification des surfaces) établit que
dans toutes surface dites orientable, on peut trouver un ensemble de boucles tel
que le découpage amène à un schéma polygonal. De plus il existe un schéma
polygonal canonique pour chaque surface. Plus le schéma est complexe, plus la
surface est complexe. Les surfaces non-orientables, comme la
[bouteille de Klein](https://fr.wikipedia.org/wiki/Bouteille_de_Klein) peuvent
être construite et caractérisée de manière similaire.

Pour en savoir plus, notamment sur les aspects algorithmiques, voir  
[ce document](http://monge.univ-mlv.fr/~colinde/cours/all-algo-embedded-graphs.pdf).

