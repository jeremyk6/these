\chapter*{Introduction}
\addcontentsline{toc}{chapter}{Introduction}

% mots-clés : inclusion, transport en commun, signalisation, outils (technologie, dispositifs)

% Contexte autour de la déficience visuelle

La déficience visuelle correspond à la perte de tout ou partie de la vue. En France, 1,7 million de personnes sont concernées par la déficience visuelle \todo{Voir dernière enquête HS du Ministère de la Santé}. Selon le degré de cécité, cela impacte l’autonomie des personnes dans leur quotidien et la mobilité en est un enjeu majeur. Elle nécessite alors des compétences particulières pour se repérer dans l'espace et analyser son environnement. Ces dernières peuvent s'acquérir auprès d'un \ipa{}, qui accompagnera la personne pour l'aider à compenser l'absence de vision par l'usage d'autres sens comme l'ouïe ou le toucher. Lors de mises en situation, ou pour documenter un itinéraire, l'\ipa{} pourra également réaliser une carte en relief du lieu étudié. Cette pratique, coûteuse en temps, est généralement artisanale et peut être réalisée à l'aide d'aimants, ou sur papier thermogonflé en décalquant une photographie aérienne. \todo{Parler de l'enquête Homère}.

% Le projet ACTIVmap et ses objectifs

\newpar

Le projet ACTIVmap, pour Assistance à la Conception de carTes pour défIcients Visuels, est un projet ANR commencé en 2020 pour une durée de quatre ans. Il regroupe trois laboratoires aux spécialités complémentaires : le LASTIG en information géographique, l'IRIT en interaction homme-machine et le LIMOS en informatique, ainsi que l'entreprise FeelObject spécialisée dans la conception de cartes tactile audiodécrites. L'objectif du projet est de proposer des méthodes et outils d'aide à la génération de cartes tactiles mobilisables par les \ipas{}. Par ailleurs, le projet s'intéresse à l'adjonction d'audiodescriptions aux cartes pour augmenter leur portée et leur efficacité. Pour assurer la pérennité et la reproductibilité des réalisations, celles-ci se basent sur des données sous licence libre.

L'espace d'expérimentation choisi se concentre sur les carrefours urbains. Ils représentent, à l'instar des espaces ouverts, une difficulté importante dans le déplacement des \pcdvs{} en ville par leur potentielle complexité. Il est ainsi nécessaire d'étudier attentivement la configuration et l'équipement d'un carrefour pour pouvoir le traverser en sécurité.

% Comment cette thèse s’inscrit dans le projet

\newpar

Cette thèse s'inscrit dans le projet en s'intéressant spécifiquement à la génération automatique d'audiodescriptions de carrefour depuis des données géographique. L'approche choisie est pluridisciplinaire : elle mobilise des connaissances et outils d'acquisition et de traitement de données issues de la géomatique, et de formalisation issues de l'informatique.

\newpar

Ce mémoire est composé de six chapitres.

Le premier chapitre consacré à l'état de l'art abordera la manière dont les \pcdvs{} se repèrent dans l'espace urbain, en s'intéressant aux pratiques et dispositifs existants. Il définira ensuite ce qu'est une donnée d'accessibilité, en examinant les bases existantes. Puis il abordera ensuite les travaux existants qui s'intéressent à la génération de représentations tactiles et textuelles de données géographiques, en particulier celles qui concernent les carrefours. Enfin, le chapitre introduira les contributions de ce travail.

Le second chapitre s'intéresse à la modélisation d'un carrefour urbain. Dans un premier temps, il détaille la représentation en branches habituellement mobilisée par les \pcdvs{} et les besoins de descriptions des traversées. Il explore ensuite les capacités d'OpenStreetMap pour représenter un carrefour du point de vue d'un usager vulnérable. En s'appuyant sur les éléments précédents, il présente une abstraction du carrefour sous la forme d'un modèle objet instanciable depuis OpenStreetMap.

Le troisième chapitre s'appuie sur la modélisation du carrefour pour explorer les différents paradigmes de description. Il se concentre ensuite sur les possibilités de personnalisation de celles-ci pour les adapter à de nouveaux usages. Puis, il expose des méthodes de spatialisation du texte pour produire une carte audiodécrite.

Le quatrième chapitre présente les trois implémentations réalisées selon les méthodes décrites dans les chapitres précédents. La première correspond à un prototype de description égocentrée sous la forme d'un document hypertexte. La seconde part du graphe OpenStreetMap pour réaliser la description exocentrée. La troisième implémente le pipeline partant de la donnée géographique au texte au sein d'un plugin QGIS.

Le cinquième chapitre se concentre sur les évaluations des différents travaux. \todo.

Enfin, le chapitre de conclusion réalise une synthèse des travaux réalisés et évoque les différentes perspectives qu'il laisse entrevoir.

% Positionnement disciplinaire de la thèse : comment je place mon travail par rapport aux informaticiens, aux géographes, et aux informaticiens.