# active_context.md

version: 1.1
status: active
scope: live_project_state
priority: medium
language: fr

---

## Rôle du fichier

`active_context.md` contient l’état actif du travail en cours.

Il sert à maintenir une continuité opérationnelle entre les sessions.
Il ne définit ni l’identité d’Atlas, ni les règles globales du système, ni les profils utilisateurs détaillés.

Il conserve :
- le chantier principal en cours,
- l’objectif actuel,
- l’état d’avancement réel,
- les éléments déjà validés,
- les points encore ouverts,
- la prochaine étape utile,
- les éventuels points de vigilance.

---

## Projet actif principal

Construction d’une mémoire externe pour Atlas.

Objectif :
permettre à Atlas de conserver une identité stable, de reconnaître l’utilisateur actif, d’adapter son approche selon le profil identifié, et de reprendre les projets sans perte de continuité d’une conversation à l’autre.

---

## Intention du projet

Créer une architecture mémoire claire, exploitable et évolutive, capable de :

- stabiliser le comportement global d’Atlas,
- différencier les utilisateurs d’un compte partagé,
- améliorer la continuité entre les sessions,
- éviter les pertes d’information critiques,
- permettre une personnalisation cohérente,
- structurer les projets suivis dans le temps,
- soutenir une spécialisation progressive selon les besoins réellement rencontrés.

---

## État actuel du chantier

Le projet a déjà franchi plusieurs étapes structurantes.

### Éléments validés

- le besoin d’une mémoire externe Atlas a été confirmé,
- le compte est partagé entre plusieurs utilisateurs, ce qui impose une logique d’identification,
- la logique de personnalisation en deux niveaux a été retenue :
  1. identifier l’utilisateur actif ;
  2. adapter la réponse selon son profil,
- `rules.md` a été validé dans une version consolidée,
- `profile.md` a été validé dans une version consolidée,
- le rôle de `active_context.md` a été clarifié,
- un template de fiche utilisateur a été rédigé,
- plusieurs fiches utilisateurs ont déjà été produites.

### Fichiers déjà cadrés ou rédigés

- `rules.md` : validé
- `profile.md` : validé
- `active_context.md` : à intégrer
- `users/<prenom>.md` : template défini
- `users/yann.md` : rédigé
- `users/maxime.md` : rédigé
- `users/loic.md` : rédigé
- `users/valentin.md` : rédigé
- `users/blandine.md` : encore à rédiger

---

## Ordre de travail retenu

1. `rules.md`
2. `profile.md`
3. `active_context.md`
4. fiches utilisateurs
5. fichiers projets / logs / sessions selon la structure finale retenue

Cet ordre reste valide.
Les fiches utilisateurs ont déjà commencé avant finalisation complète du noyau, ce qui reste acceptable tant que l’ensemble est ensuite harmonisé.

---

## Point de doctrine important

Le projet ne doit pas dériver vers un faux avancement fondé sur des formulations séduisantes mais peu opératoires.

La priorité reste :
- une ossature claire,
- des fichiers réellement distincts dans leur fonction,
- une architecture mémoire exploitable,
- une reprise fiable des projets et utilisateurs.

Principe directeur :
**structure utile avant sophistication.**

---

## Décisions déjà prises

### Identification
Atlas doit demander l’identité de la personne qui parle au début d’une nouvelle conversation, sans lister les utilisateurs connus.

### Personnalisation
Atlas doit adapter sa réponse selon l’utilisateur identifié, sans perdre son identité centrale.

### Mémoire
La mémoire doit rester sélective, structurée et utile.
Elle ne doit pas devenir un stockage indiscriminé.

### Continuité
Un projet doit pouvoir être repris sans repartir de zéro.

### Hiérarchie des fichiers
`rules.md` commande la logique générale.  
`profile.md` fixe l’identité stable.  
`active_context.md` suit le chantier vivant.  
Les fiches utilisateurs portent la personnalisation fine.

---

## Point actuellement en cours

Stabiliser et intégrer `active_context.md` dans le repo comme fichier de suivi opérationnel.

Le point à préserver :
ce fichier doit suivre l’état réel du chantier, sans redéfinir ni la philosophie générale du projet ni l’identité d’Atlas.

---

## Prochaine étape utile

Après intégration de `active_context.md` :

1. rédiger `users/blandine.md` ;
2. harmoniser les fiches utilisateurs déjà produites ;
3. préparer la structure des fichiers annexes (`sessions`, `summaries`, `logs`) selon l’usage réel.

---

## Points de vigilance

- ne pas mélanger règles globales, identité Atlas, contexte actif et profils utilisateurs,
- ne pas surcharger un fichier avec plusieurs fonctions,
- ne pas figer trop tôt les utilisateurs dans des descriptions rigides,
- ne pas confondre mémoire utile et accumulation de détails,
- garder une architecture simple à maintenir,
- harmoniser les fichiers déjà rédigés avant extension du système.

---

## État synthétique

Le projet est dans une phase de fondation structurelle avancée.

Ce qui est déjà bien posé :
- logique du système,
- procédure d’identification,
- structure générale de la mémoire,
- `rules.md`,
- `profile.md`,
- template des fiches utilisateurs,
- plusieurs profils utilisateurs rédigés.

Ce qui reste à consolider immédiatement :
- intégration de `active_context.md`,
- rédaction de `users/blandine.md`,
- harmonisation des fiches existantes,
- préparation des fichiers annexes.

---

## Résumé opératoire

Projet en cours :
mémoire externe Atlas

But actuel :
stabiliser le noyau du système et aligner les fichiers déjà produits

Étape actuelle :
intégration de `active_context.md`

Étape suivante :
création de `users/blandine.md`

Risque principal :
produire des fichiers intéressants mais insuffisamment harmonisés entre eux

Ligne de conduite :
faire peu, mais propre, distinct, réutilisable et durable
