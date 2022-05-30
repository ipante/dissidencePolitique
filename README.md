# Votes-dissidents-au-conseil-national
Visualisation des votes "dissidents" des conseiller nationaux par rapport à leur groupe parlementaire. Les données sont constituées des treize premières sessions parlementaire de la 51ème législature ( 2 décembre 2019 - 18 mars 2022).

## Description

## Données
### Acquisition des donées
Les votes des conseillers nationaux sont en libre téléchargement en format XLS sur le site du [parlement suisse](https://www.parlament.ch/fr/ratsbetrieb/abstimmungen/abstimmung-nr-xls).

### Traitement des données
La première étape a été de compter pour chaque groupe parlementaire et pour chaque votation, le nombre de voix exprimées en faveur du texte, en sa défaveur et le nombre d'abstention. Il a fallu ensuite déterminer quelle sous-groupe _(Oui / Non / Abstention)_ a receuilli le plus grand nombre de voix au sein de chaque groupe parlementaire afin de pouvoir déduire les personnes ayant exprimé une divergence. La dernière étape a été de dégager l'existence ou non d'une "consigne de vote" (cf [méthodologie](#Méthodologie)) pour ensuite créer la liste des personnes s'étant exprimés contre celle-ci. 
Pour plus d'informations le fichier j'ai déposé en guise d'exemple les résultats de mon analyse pour la [13ème session parlementaire](5113_prêt.xlsb.xlsx).

## Méthodologie
### Détérmination de l'existence ou de l'absence d'un avis majoritaire 
Dans l'optique de ne comptabiliser que les personnes ayant votés différement d'une supposée consigne de vote ou _a minima_ différement de l'avis majoritaire du groupe parlementaire auqel ils appartiennent, il était nécessaire de définir un seuil en dessous duquel les voix étaient trop dispersées pour considérer qu'un avis majoritaire existait à l'intérieur du groupe. Pour chaque vote est donc calculé un taux de dispersion des voix : il s'agit du nombre de votes exprimés dans le sens majortaire par rapport au nombre de votes exprimés total.

## Outils utilisés


## Limites
Abstention =pas Non sauf que dans mon projet oui

## Contexte du projet
Ce projet a été réalisé par Théo Rochat dans le cadre du cours de _Visualisation de données (SP22)_ donné par Isaac Pante à l'Université de Lausanne.
