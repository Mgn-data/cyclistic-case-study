# cyclistic-case-study

Étude de cas : comment les membres et les occasionnels utilisent-ils les vélos ? (Google Sheets)

## Contexte

Cyclistic propose des vélos en libre-service à Chicago. L'objectif de l'équipe marketing est simple : convaincre les utilisateurs occasionnels de prendre un abonnement annuel, bien plus rentable pour l'entreprise.

Ce projet est mon étude de cas pratique réalisée dans le cadre du certificat Google Data Analytics sur Coursera.

## Données

J'ai travaillé sur deux jeux de données réels mis à disposition par Motivate International Inc., représentant près de 800 000 trajets :

- 1er trimestre 2019 : 365 071 lignes
- 1er trimestre 2020 : 426 887 lignes

## Outil

Google Sheets : formules de calcul, filtres, tableaux croisés dynamiques et visualisations graphiques.

## Méthode

1. Préparation : calcul de la durée réelle de chaque trajet et extraction du jour de la semaine.
2. Nettoyage : suppression des trajets aberrants (plus de 24 h ou moins d'une minute) et vérification des doublons et des cases vides (aucun trouvé sur les colonnes essentielles).
3. Exploration : comparaison des volumes, calcul des moyennes, des médianes et observation des habitudes selon les jours.
4. Restitution : création de graphiques clairs et pistes d'actions concrètes pour le marketing.

## Principaux résultats

- Des trajets 3 fois plus longs pour les occasionnels : leur durée médiane est d'environ 23 minutes, contre seulement 8 à 9 minutes pour les membres abonnés (tendance identique en 2019 et 2020).
- Une utilisation marquée par le week-end : les occasionnels roulent beaucoup plus le week-end que les membres (42 % de leurs trajets en 2019, 50 % en 2020, contre 16 à 17 % chez les membres abonnés).
- Une part d'occasionnels qui progresse : ils représentaient environ 6 % des trajets début 2019, contre 10,6 % début 2020.

## Limites

Ces chiffres portent uniquement sur les trois premiers mois de l'année (période hivernale à Chicago) et ne permettent pas d'expliquer les causes de ces différences. Pour confirmer ces tendances et adapter les campagnes sur toute l'année, il faudrait comparer avec les données des beaux jours.

## Rapport complet

Retrouve le détail de mes analyses et graphiques dans le document complet : [rapport-cyclistic.pdf](rapport-cyclistic.pdf).
