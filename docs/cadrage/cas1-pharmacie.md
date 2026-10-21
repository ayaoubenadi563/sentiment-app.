# Fiche de cadrage : Ordonnances incomplètes en pharmacie

## Besoin en une phrase (obligatoire)

Détecter les informations manquantes dans les ordonnances afin d'aider le pharmacien à vérifier les prescriptions avant la délivrance des médicaments.

## Utilisateur final (obligatoire)

Le pharmacien utilise l'application pour repérer rapidement les informations absentes ou incomplètes sur une ordonnance. Il reste responsable de la vérification et de la décision finale.

## Données nécessaires

Les données nécessaires sont des exemples d'ordonnances contenant les médicaments, les dosages et les informations du prescripteur. Elles doivent être anonymisées et vérifiées avant leur utilisation.

## Métrique de succès

Le système doit détecter correctement les champs manquants sur un jeu de test validé. Le taux de détection et le nombre de fausses alertes permettront d'évaluer les performances.

## Conséquence d'une erreur

Une information manquante non détectée peut contribuer à une erreur de délivrance ou à un risque pour le patient. Toute alerte doit être vérifiée par le pharmacien avant la délivrance.

## Risques éthiques

Les ordonnances peuvent contenir des données médicales sensibles. Il faut protéger les données personnelles, limiter les accès et éviter toute décision automatique pouvant mettre le patient en danger.

## Approche retenue

- [x] Règles métier
- [ ] Machine Learning supervisé
- [ ] Modèle de langage (LLM)

## Justification

Les règles métier conviennent car les champs obligatoires sont définissables explicitement (a). La vérifiabilité facilite le contrôle des résultats (b), tandis que les conséquences d'une erreur justifient une validation humaine systématique (d).

## Approche écartée et pourquoi (facultatif)

Le Machine Learning et les modèles de langage ne sont pas retenus en première approche, car ils peuvent produire des résultats incorrects et demandent une validation rigoureuse dans un contexte médical.