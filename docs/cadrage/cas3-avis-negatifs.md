# Fiche de cadrage : Analyse des avis négatifs

## Besoin en une phrase (obligatoire)

Identifier les avis clients négatifs afin de repérer les problèmes récurrents et d'aider l'équipe à améliorer la qualité du service.

## Utilisateur final (obligatoire)

Les responsables du service client et les équipes qualité utilisent les résultats pour comprendre les motifs d'insatisfaction et prioriser les actions correctives.

## Données nécessaires

Les données nécessaires sont des avis clients textuels accompagnés, si possible, d'une note et d'une date. Les données personnelles doivent être supprimées ou anonymisées avant l'analyse.

## Métrique de succès

La qualité sera évaluée en comparant les avis classés par le système à un échantillon annoté manuellement. La précision, le rappel et le nombre d'erreurs de classification permettront de mesurer les performances.

## Conséquence d'une erreur

Un avis positif classé comme négatif peut fausser les priorités de l'équipe, tandis qu'un avis négatif ignoré peut masquer un problème important. Les résultats doivent être vérifiés avant toute décision majeure.

## Risques éthiques

Les avis peuvent contenir des informations personnelles ou refléter des biais linguistiques. Il faut protéger les données, limiter les biais de classification et éviter de tirer des conclusions excessives à partir d'un avis isolé.

## Approche retenue

- [ ] Règles métier
- [x] Machine Learning supervisé
- [ ] Modèle de langage (LLM)

## Justification

Le Machine Learning supervisé peut apprendre à classer les avis à partir d'exemples annotés (a). La précision et le rappel permettent de mesurer la qualité des résultats de façon vérifiable (b), tandis que les conséquences d'une erreur imposent de contrôler les classifications avant d'agir (d).

## Approche écartée et pourquoi (facultatif)

Les règles métier seules détectent difficilement toutes les formulations et nuances du langage. Un modèle de langage n'est pas retenu initialement afin de privilégier une approche entraînable et évaluable sur un jeu d'exemples annotés.