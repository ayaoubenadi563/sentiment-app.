# Fiche de cadrage : Questions sur le règlement intérieur

## Besoin en une phrase (obligatoire)

Permettre aux utilisateurs de retrouver rapidement les règles du règlement intérieur et d'obtenir des réponses fondées sur le document de référence.

## Utilisateur final (obligatoire)

Les employés et les responsables utilisent l'application pour consulter les règles internes et comprendre les procédures applicables à leur situation.

## Données nécessaires

Les données nécessaires comprennent les versions officielles et à jour du règlement intérieur, organisées par rubrique. Chaque document doit être identifié par sa version et sa date de mise à jour.

## Métrique de succès

Le système sera évalué selon la pertinence des réponses et la proportion de réponses correctement appuyées par le règlement. Les réponses sans preuve suffisante devront être signalées.

## Conséquence d'une erreur

Une réponse incorrecte peut conduire un employé à mal comprendre une règle ou à suivre une procédure inadaptée. Les réponses doivent renvoyer aux passages pertinents du document officiel.

## Risques éthiques

Les règles internes peuvent être mal interprétées si le contexte est incomplet ou si le document est obsolète. Il faut protéger les informations confidentielles et permettre à l'utilisateur de vérifier la source.

## Approche retenue

- [ ] Règles métier
- [ ] Machine Learning supervisé
- [x] Modèle de langage (LLM)

## Justification

Un modèle de langage peut reformuler les informations du règlement en langage naturel (a). La vérifiabilité doit être assurée par des citations des passages sources (b), et les conséquences d'une erreur imposent de signaler les réponses incertaines et de renvoyer au document officiel (d).

## Approche écartée et pourquoi (facultatif)

Les règles métier seules ne permettent pas toujours de répondre à des questions formulées de nombreuses façons. Le Machine Learning supervisé nécessiterait des exemples de questions et de réponses validées en quantité suffisante.