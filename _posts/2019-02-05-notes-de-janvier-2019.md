---
layout: post
title: Notes de janvier
redirect_from: "/2019/02/05/notes-de-janvier-2019/"
permalink: notes-de-janvier-2019
---

Quelques notes de janvier.

---

![](assets/ciel.png){: .center-image width="85%"}

---

## Rediffusion de géométrie aléatoire

*Images des maths* rediffuse un 
[article à propos de la géométrie aléatoire](http://images.math.cnrs.fr/A-quoi-ressemble-un-planisphere-vraiment-aleatoire.html)
pour fêter l'[attribution du prix Wolf à Jean-François Le Gall](http://www.actu.u-psud.fr/fr/recherche/actualites-2019/jean-francois-le-gall-laureat-du-prix-wolf-de-mathematiques.html). 
L'article de [Nicolas Curien](https://www.math.u-psud.fr/~curien/)
donne quelques résultats surprenants sur les [cartes planaires](https://fr.wikipedia.org/wiki/Carte_combinatoire),
c'est-à-dire les graphes plongés dans le plan. 
Entre autres choses surprenantes :
le concept est étudié dans l'optique d'une unification de la relativité générale 
et de la mécanique quantique (!). 

Un document sur cette thématique est 
l'[habilitation de Guillaume Chapuy](https://www.irif.fr/~chapuy/chapuyHabilitationWeb.pdf),
qui semble très bien écrite et que j'espère lire un jour.

(Si vous êtes fanatique de cartes, il y a une 
[«journée carte»](http://cartaplus.math.cnrs.fr/JourneesCartes/) 
de prévue le 15 février à Paris.)

## LIPIcs sans logos

J'aime bien la classe latex LIPICs qui est utilisée par la plupart des 
conférences ayant choisi l'accès ouvert. 
Pour l'utiliser dans d'autres contextes 
que ces conférences, par exemple pour des versions arxiv, il y avait jusqu'à 
récemment quelques difficultés: des logos, des références au numéro doi etc. 
Suivant l'exemple d'un collègue, j'avais modifié le fichier de classe, mais 
c'est désormais inutile : la commande \hideLIPICs cache les informations 
non-pertinentes. (Voir les
[recommendations aux auteurs](http://drops.dagstuhl.de/styles/lipics-v2019/lipics-v2019-authors/lipics-v2019-authors-guidelines.pdf), 
page 8.)

## Apprentissage profond et apprentissage PAC

L'apprentissage profond est très populaire auprès d'à peu près tout le monde 
(d'un point de vue purement technique), sauf des informaticiens théoriciens qui 
lui reprochent son manque de garanties théoriques. 
Plusieurs groupes de recherches essayent de combler ce vide (par exemple 
[autour d'Alexander Mądry](http://people.csail.mit.edu/madry/lab/)
et du [ML theory group à Princeton](http://mltheory.cs.princeton.edu/)). 

Un des cadres rigoureux d'analyse de l'apprentissage est 
l'[apprentissage PAC](https://fr.wikipedia.org/wiki/Apprentissage_PAC), et 
[des liens sont en train d'être tissés](https://theorydish.blog/2019/01/04/on-pac-analysis-and-deep-neural-networks/) 
entre les deux.

En parlant de PAC, Leslie Valiant a publié un [livre](http://www.probablyapproximatelycorrect.com/)
disponible en français, à propos de ce concept (dont il est l'inventeur), et de 
ses liaisons avec la nature et l'évolution.

## Éoliennes, apprentissage et algorithmes

Lance Fortnow [bloguait ce mois-ci](https://blog.computationalcomplexity.org/2019/01/machine-learning-and-wind-turbines.html)
à propos des éoliennes et de l'apprentissage. 

En un mot, les changements soudain de force et de direction du vent sont un 
problème récurrent pour les éoliennes, et causent de nombreux dégats si ils ne 
sont pas anticipés. Il est possible d'utiliser des simulations de mécaniques des 
fluides, mais c'est plutôt lent, et la tendance est à l'utilisation de 
l'apprentissage pour faire des prévisions rapides. 

Ainsi, il existe une manière bien définie/comprise de procéder, mais l'on 
préfère l'apprentissage pour sa rapidité. Cela m'a rappelé un 
[sujet sur stack exchange](https://cstheory.stackexchange.com/questions/38095/if-machine-learning-techniques-keep-improving-whats-the-role-of-algorithmics-i)
qui posait la question suivante : les algorithmes seront-ils encore utiles dans 
le futur (sachant que pour la majorité des problèmes que nous avons à résoudre, 
nous n'avons pas besoin d'une solution parfaite, et le plus souvent nous ne 
pouvons même pas mesurer la qualité de la solution) ? 
Malheuresement la question n'a pas reçu beaucoup de réponses... 

## Au-delà du pire cas et complexité fragile

Une nouvelle approche de recherche en informatique théorique consiste à aller 
«au-delà de la complexité dans le pire cas» (*«beyond worst-case»*), 
c'est-à-dire à considérer d'autres mesures d'efficacité que le temps de calcul 
sur la pire instance, puisque cette dernière est parfois (souvent ?) peu 
pertinente. Il y a beaucoup de bonnes choses à découvrir dans ce domaine, comme 
la [complexité lisse](Analyse lisse d'algorithme). Voir aussi les
[top 10 ideas](http://timroughgarden.org/f14/l/top10.pdf) du domaine par 
[Tim Roughgarden](http://timroughgarden.org/).

Ce mois-ci, une nouvelle mesure est définie dans un 
[papier arxiv](https://export.arxiv.org/abs/1901.02857) : la
 complexité fragile. J'ai juste lu le résumé, et je ne comprends pas en quoi 
cette mesure est fragile, mais je comprends la définition dans le cas du tri : 
la complexité fragile d'un algorithme de tri sur une instance donnée est le 
nombre maximum de fois qu'un élément est comparé. 


