# Ethel — Thèse d'exercice de pharmacie

Ce dépôt accompagne la finalisation d'une **thèse d'exercice de pharmacie**
(Diplôme d'État de Docteur en Pharmacie), en français.

## Skill inclus : `relecture-these-pharmacie`

Un skill Claude Code autonome et francophone de **relecture critique et de
finalisation** de la thèse. Il est chargé automatiquement quand on ouvre ce dépôt
avec Claude Code (il vit dans `.claude/skills/`).

### Ce qu'il fait

Une relecture de niveau jury, entièrement en français, en 6 modes :

1. **Structure & complétude** — vérifie les pièces obligatoires d'une thèse
   d'exercice (serment de Galien, résumé/abstract, abréviations, pagination…).
2. **Jury de soutenance** — simule Président, Directeur et assesseur praticien ;
   fournit des questions probables d'oral.
3. **Audit bibliographique Vancouver** — appels ↔ références, format, sources.
4. **Langue & style académique** — registre, typographie française, DCI, unités.
5. **Cohérence & argumentation** — fil conducteur, objectifs ↔ conclusion.
6. **Vérification factuelle ciblée** — plausibilité des affirmations clés.

Les retours sont **hiérarchisés** (🔴 Bloquant · 🟠 Important · 🟡 À améliorer ·
🔵 Cosmétique) et l'auteur garde la décision finale : le skill **ne réécrit jamais
silencieusement** et **n'invente aucune référence**.

### Comment l'utiliser

1. Placer le manuscrit (`these.docx` ou `.pdf`) dans ce dépôt.
2. Ouvrir le dossier avec Claude Code (`claude`).
3. Demander, par exemple :
   > « Relis ma thèse `these.docx` en mode jury complet, en français, et donne-moi
   > une liste de corrections priorisées. »

### Fiches de référence (`.claude/skills/relecture-these-pharmacie/references/`)

- `structure-these-exercice.md` — plan-type et checklist de complétude.
- `style-vancouver.md` — règles de citation Vancouver + exemples.
- `checklist-jury.md` — grille d'évaluation façon jury.
- `langue-et-style.md` — style académique et typographie françaises.
