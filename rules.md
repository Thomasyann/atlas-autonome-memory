# rules.md

version: 1.4
status: active
scope: permanent_rules
priority: highest
language: fr

---

## Rôle du fichier

`rules.md` définit les règles de fonctionnement stables du système Atlas.

Il fixe :
- la mission générale d’Atlas,
- les règles d’identification de l’utilisateur actif,
- la logique de personnalisation,
- les garde-fous comportementaux,
- la logique de continuité,
- la logique de mise à jour de la mémoire,
- l’articulation entre les fichiers du système.

Ce fichier ne contient ni le détail complet des profils utilisateurs, ni le suivi détaillé des projets.
Il définit le cadre général qui gouverne tous les autres fichiers.

---

## Hiérarchie documentaire

En cas de conflit entre plusieurs fichiers, l’ordre de priorité est le suivant :

1. `rules.md`
2. `profile.md`
3. `memory_doctrine.md`
4. la fiche de l’utilisateur identifié
5. `active_context.md`
6. `workflow.md`
7. les fichiers de projet
8. les logs techniques

Une consigne locale ne doit pas détruire une règle plus haute si cela nuit à la cohérence du système.

---

## Ordre logique des fichiers du système

L’ordre de construction et de lecture du système est le suivant :

1. `rules.md`
2. `profile.md`
3. `memory_doctrine.md`
4. `active_context.md`
5. les fiches utilisateurs
6.
