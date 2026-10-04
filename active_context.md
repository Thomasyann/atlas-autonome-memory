# active_context.md

version: 1.3
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
- soutenir une spécialisation progressive selon les besoins réellement rencontrés,
- construire une mémoire alimentée par la conversation en cours avec l’utilisateur identifié, sans logique de surveillance transversale.

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
- `memory_doctrine.md` a été rédigé comme logique d’extraction et de stabilisation de la mémoire,
- `workflow.md` a été rédigé comme description du cycle opérationnel réel d’Atlas,
- le rôle de `active_context.md` a été clarifié,
- un template de fiche utilisateur a été rédigé,
- les cinq fiches utilisateurs ont été produites.

### Fichiers déjà cadrés ou rédigés

- `rules.md` : validé
- `profile.md` : validé
- `memory_doctrine.md` : validé
- `workflow.md` : rédigé
- `active_context.md` : à harmoniser / maintenir
- `users/<prenom>.md` : template défini
- `users/yann.md` : rédigé
- `users/maxime.md` : rédigé
- `users/loic.md` : rédigé
- `users/valentin.md` : rédigé
- `users/blandine.md` : rédigé

---

## Ordre de travail retenu

1. `rules.md`
2. `profile.md`
3. `memory_doctrine.md`
4. `active_context.md`
5. fiches utilisateurs
6. `workflow.md`
7. fichiers projets / logs selon les besoins réels

Cet ordre reste valide.
Les fiches utilisateurs ont été rédigées avant harmonisation complète finale, ce qui reste acceptable tant que l’ensemble est ensuite aligné.

---

## Point de doctrine important

Le projet ne doit pas dériver vers un faux avancement fondé sur des formulations séduisantes mais peu opératoires.

La priorité reste :
- une ossature claire,
- des fichiers réellement distincts dans leur fonction,
- une architecture mémoire exploitable,
- une reprise fiable des projets et utilisateurs,
- une alimentation de la mémoire qui ne repose pas sur la surveillance manuelle des conversations d’autres membres de la famille.

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

### Doctrine mémoire
Atlas doit être capable d’extraire dans l’échange présent les informations utiles à la relation, en distinguant :
- signal faible,
- hypothèse relationnelle,
- tendance probable,
- trait durable.

### Workflow
Atlas doit suivre un cycle opérationnel stable :
- identifier,
- charger les bons repères,
- conduire l’échange,
- observer,
- classer,
- décider d’une éventuelle mise à jour.

### Continuité
Un projet doit pouvoir être repris sans repartir de zéro.

### Hiérarchie des fichiers
`rules.md` commande la logique générale.  
`profile.md` fixe l’identité stable.  
`memory_doctrine.md` définit la logique d’apprentissage relationnel.  
`active_context.md` suit le chantier vivant.  
`workflow.md` décrit le cycle opérationnel.  
Les fiches utilisateurs portent la personnalisation fine.

---

## Point actuellement en cours

Passe d’harmonisation croisée du noyau du système.

Objectif :
vérifier que `rules.md`, `profile.md`, `memory_doctrine.md`, `workflow.md`, `active_context.md` et les fiches utilisateurs racontent exactement la même architecture, sans doublons ni contradictions.

---

## Prochaine étape utile

Après harmonisation finale :

1. maintenir les fichiers noyaux stables ;
2. définir éventuellement une structure minimale de `logs/` pour les aspects techniques uniquement ;
3. laisser `sessions/` et `summaries/` hors du cœur du système tant qu’un besoin réel et moralement propre ne justifie pas leur retour ;
4. commencer à tester la logique réelle d’enrichissement mémoire à partir des conversations en cours avec les utilisateurs identifiés.

---

## Points de vigilance

- ne pas mélanger règles globales, identité Atlas, logique mémoire, contexte actif, workflow et profils utilisateurs,
- ne pas surcharger un fichier avec plusieurs fonctions,
- ne pas figer trop tôt les utilisateurs dans des descriptions rigides,
- ne pas confondre mémoire utile et accumulation de détails,
- ne pas recréer une logique assimilable à de la surveillance,
- garder une architecture simple à maintenir,
- harmoniser les formulations avant toute nouvelle extension.

---

## État synthétique

Le projet est dans une phase de fondation structurelle avancée.

Ce qui est déjà bien posé :
- logique du système,
- procédure d’identification,
- structure générale de la mémoire,
- `rules.md`,
- `profile.md`,
- `memory_doctrine.md`,
- `workflow.md`,
- `active_context.md`,
- template des fiches utilisateurs,
- cinq profils utilisateurs rédigés.

Ce qui reste à consolider immédiatement :
- harmonisation fine entre les fichiers,
- clarification éventuelle du rôle minimal de `logs/`,
- mise en pratique progressive de la doctrine mémoire dans les échanges réels.

---

## Résumé opératoire

Projet en cours :
mémoire externe Atlas

But actuel :
stabiliser le noyau du système et harmoniser les fichiers déjà produits

Étape actuelle :
passe d’harmonisation croisée

Étape suivante :
éventuelle structure minimale de `logs/` puis test réel de l’enrichissement mémoire dans les conversations identifiées

Risque principal :
produire des fichiers cohérents séparément mais encore légèrement désalignés entre eux

Ligne de conduite :
faire peu, mais propre, distinct, réutilisable et durable
