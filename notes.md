Faiblesses d'un plan du type :
	- Limiter les répétitions sur la mise en oeuvre

Choses dont il faut parler:
	- Parler du Pigeon Nelson
	- Parler du pipeline/des plateformes
	- Schématisation du carrefour
	- Quelle est ma contribution à l'outil de segmentation des carrefours ?

Mots qui manquent:
	- Données
	- Formalisation (modélisation + description)
	- Évaluation (toutes les descriptions)
	- Évaluation de l'objet + évaluation de l'implémentation

Évaluation théorique d'un algorithme:
	- Question : comment une personne peut l'étendre ?
	- Quelle est son périmètre ? Quels sont les cas limites ?

Partie IV : Est-on capable de décrire l'intégralité des descriptions avec le système mis en œuvre ? Est-ce que la proposition théorique est limitante ? Est-ce que l'implémentation et l'environnement sont limitants ?

Définir les termes. Définir le périmètre de son action. Dérouler des exemples de descriptions et la manière de les obtenir : comment intégrer les données, comment les traiter, comment les intégrer à la description.

Chapitre implémentation qui décrit les choix techniques et l'évaluation de l'implémentation ? 
Présenter à la soutenance de manière différente du plan de thèse

Organisation : 
- À faire en premier : décider des évaluations que tu vas faire
- De manière générale : avoir une idée de toutes les tâches qu'il reste à faire pour la rédaction

II.4 : Quels-sont les verrous scientifiques ? (à quoi je m'attaque ?)

Les chapitres III et IV sont des chapitres de contribution, pas d'état de l'art. Les papiers importants, ceux sur lesquels je m'appuie fortement sont présents dans l'état de l'art.

Conclusion : Prise de recul : quelles sont mes contributions en informatique et en géomatique (scientifiques, applicatives) ?

Comment évaluer la description égocentrée et la description exocentrée ? Ce sont des textes "par défaut" produits comme exemple de but à générer automatiquement. Il faudra évaluer l'outil final et sa capacité à générer plusieurs modalités de descriptions (exocentré, égocentré, ajout de données).

Quelles sont mes contributions principales ? Ce sont elles qui nécessitent une évaluation.

Plans :
    Implémentation avant évaluation, car nécessité d'évaluer en tenant compte des éventuelles limites de l'implémentation.

Outils à mobiliser :    
 - Paquet LaTeX français.
 - Correcteur orthographique/grammatical dans le navigateur (Grammalecte, Grammarly)

Le carrefour dont vous êtes le héros : proposition non-évaluée (en tant qu'outil). On peut exposer des idées sur la manière dont on pourrait l'évaluer dans le manuscrit. Reconstruire le raisonnement et expliquer comment ce travail se positionne.

Tâches restantes pour la rédaction:
- Évaluer le module INRAE sur ADUM
- Trier mes références bibliographiques
- "Dataminer" Mattermost
- Déterminer comment évaluer les descriptions textuelles
- Terminer l'implémentation du plugin QGIS + générer une description des arrêts de bus (côté test de l'implémentation)
- Définir un style LaTeX

- Jury de thèse : qui ? Rapporteurs avant l'été.
    - Rapporteurs :
        - Myriam Servière
        - Didier Josselin
    - Examinateurs :
        - Mathieu Simonet (https://www.imt-atlantique.fr/fr/personne/mathieu-simonnet)
        - Anke Brock
        - Valérie Gyselinck
        - Florence Gaunet (ne travaille plus sur le sujet depuis 15 ans)
        - (to be continued)

_______

Notes accessibilité : comment créer un alt text en latex pour les tableaux

Règle de Guillaume : une bonne illustration par sous-partie, construction du texte autour de l'illustration.

Partie 1.3 : comment parler des dispositifs d'interaction avec le texte ? Présenter les outils d'Okeenea. Désambigüiser l'utilité de l'outil dans la description et non dans l'itinéraire.

Un paragraphe sur toutes les méthodes de guidage "aveugle". 

________

12/07/2023

Partir de Sound and geographic visualisation, Krygier, 1994

https://link.springer.com/chapter/10.1007/978-3-319-07926-4_24

________

Est-ce que l'on peut ajouter un alt text 

_____

Forme : "Cette possibilité est exploitée par [x]" [x] = les auteurs, pas la publications. Voir comment faire (citep ?)

État de l'art : expliquer l'intérêt particulier d'une/+sieurs publications pour mon travail.

Cadre de synthèse à la fin de chaque section. Parfois pour la cohérence, le cadre est écrit avant le reste pour cadrer le discours.

________

Traversée de la rue, version StreetMix : https://streetmix.net/jeremy.kalsron/4 .

_________

citet quand je veux parler des auteurs (genre Machin et al. [42] disent (...))

__________

Carrefour : identifier les cas complexes

Une page de carrefours complexes avec commentaires pour expliquer leur complexité : pas exhaustive de la complexité.

___________

Présenter d'abord les carrefours + cas particuliers
Présenter ensuite les traversées + cas particuliers


___________

Lors du dépôt, il faut demander une extension du délai pour le rapporteur (pas de relecture pendant les vacances de noël).

_____

# Dans 2.1

Définir ce qu'est un graphe routier
- Définir ce qu'est un carrefour
	- Définir ce qu'est une branche
    - Définir ce qu'est une traversée
	- Définir ce qu'est un trottoir
	- Définir ce qu'est un îlot

Définir du flou pour la définition du carrefour dans le cas d'une branche qui ne se traverse pas.

Ce qui est de l'ordre de la définition : une traversée est un chemin = un ensemble d'arêtes.

La traversée est un chemin qui peut passer par un îlot, qui ne fait pas partie du graphe routier.
	Dans le graphe on peut identifier des nœuds précis, en indiquant des chemins qui ne sont pas dans la classe des routes. Mes îlots appartiennent à des chemins qui ne sont pas dans la classe des routes.

Théorie des graphes : notion de relation, pour définir la manière dont les choses s'organisent spatialement.

Définition graphe = définition formelle sans ambigüité. + définition textuelle pour s'adresser aux deux communautés.

Voir HDR Didier Josselin.

Dans l'esenmble des nodes qui sont des kerbs, il y a un sous ensemble de nodes.
Autres manières : on considère que les nœuds 

Définition de graphes multimodaux

https://excalidraw.com/#room=34ca2fe54b2f418751c3,xmkPzLd1nuXnPKPOGuWVVw

https://demo.hedgedoc.org/DxG6vwfQTg-DWkW5y_pO4g#

----
Réunion du 03/10 :
Remplacer couverture par partition

Définition 4 : Sortir "Cette fonction $f_t$ est appelée **fonction d'adjacence** du trottoir $G_t$." de la définition pour l'ajouter dans le corps du texte.

✅ Définition 5 : Tous les nœuds internes sont dans Vr (pas la peine de se limiter à 3 nœuds)
✅ Définition 6 : Il existe un edge qui passe des nœuds purement de la branche aux nœuds dans le cœur de carrefour. Actuellement j'indique que les nœuds sont communs, mais pas les edges.

Expliquer les propriétés des différents éléments : où s'arrête la branche ? Une branche permet de relier deux carrefours ? Exemple : un rond point à deux branches. Est-ce qu'un carrefour a un minimum de 3 branches. La définition doit inclure tous les cas bizarres qui m'intéressent, et que ça va inclure ou exclure.

--------

Réunion du 10/10

Est-ce qu'on vire les carrefours qui ne se traversent pas ?

Correction de la définition :
- [x] Un cœur de carrefour ne doit pas être un chemin (rajouter dans la définition 6)
- [x] Une couverture est un sous-graphe connexe, sauf dans le cas de deux branches qui partent d'un carrefour. Exemple : https://excalidraw.com/#room=24c0b85ef564425c64aa,RvLTnA8ZLBMc_Q2WbDzE9A. Enlever la nécessité de connexité dans la définition 1 : virer connexe partout et vérifier qu'il n'y a pas de conséquences. Il pourrait y en avoir si la connexité est importante à un endroit.

Il faut garder le cas des étudiants pour les perspectives/la conclusion pour montrer qu'il y aura besoin d'un nouveau modèle.

----------------------------

# TODO

- [ ] Partie OSM : Parler du cycle des feux pour aborder l'évolutivité de la sémantique d'OSM
- [ ] ODBL : NOTE DE BAS DE PAGE
- [ ] Mots en anglais en italique
- [ ] Figure quand tu fais un renvoi en minuscule
- [ ] Régler la césure pour le retour à la ligne des mots inconnus de LaTeX (exemple: OpenStreetMap)
- [ ] Ne pas mettre d'espace avant les : (babel ajoute un espace insécable automatiquement)
- [ ] Nombre en toute lettre

---------

Réunion du 17 octobre

2.3 oui 2.4 - Présenter le modèle du carrefour dont vous êtes le héros

2.3.3 - Présenter l'algorithmique sur le graphe pour instancier le modèle depuis OSM

3.1 - Présentation de la chaîne 

Version projetée du graphe

Modifier le plan : exo, à la carte, ego

3.3.3 - La description dans la carte

Au fur et à mesure de mes parties, j'augmente l'interaction entre l'utilisateur et la donnée/la carte/le graphe.

2.3.3.1 - Graphe routier
2.3.3.2 - Graphe piéton
2.3.3.3 - Correspondance OSM-UML

---
Réunion 07/11/2023

Notion de stroke (vrai terme). Quand tu prends une branche, si tu arrives à un autre carrefour et tu les agrèges pour avoir une enfilade de branche.
---
Réunion du 23/11

Dans la partie modélisation, on fait référence à OSM mais on peut généraliser à d'autres graphes si la donnée existe.

Perspective: qualification intrinsèque: détecter les endroits qui ont une description insuffisante pour les DV.

Conclusion : 
----
Réunion du 27/11:

- Annoncer ce qui va se passer dans chaque partie.
- Ne pas avoir deux titres qui se suivent (rajouter un morceau de phrase)
- Modèle de données pétés sur Gtihub

Partie description:

1. De la donnée au texte
2. Cas 1. Description exocentrée
3. Cas 2. Description à la carte
4. Cas 3. Description égocentré

4.2 : Ajouter en annexe les travaux d'Ali et des garçons, voire 4.4. Enrichir les descriptions.