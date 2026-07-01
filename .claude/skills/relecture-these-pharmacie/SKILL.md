---
name: relecture-these-pharmacie
description: >
  Relecture critique et finalisation d'une thèse d'exercice de pharmacie
  (Diplôme d'État de Docteur en Pharmacie) rédigée en français. À utiliser
  quand l'utilisateur veut faire relire, corriger, améliorer ou finaliser un
  mémoire / une thèse de pharmacie, simuler un jury de soutenance, vérifier des
  références en style Vancouver, contrôler la structure attendue par une UFR de
  pharmacie française, ou polir le style académique. Déclencheurs : « relis ma
  thèse », « thèse de pharma », « thèse d'exercice », « mémoire de pharmacie »,
  « préparer ma soutenance », « corrige ma bibliographie Vancouver », « retours
  du jury ». Tout le travail et tous les retours se font EN FRANÇAIS.
---

# Relecture de thèse d'exercice de pharmacie

Ce skill guide une relecture critique, exigeante et bienveillante d'une **thèse
d'exercice de pharmacie** française (soutenance pour le Diplôme d'État de Docteur
en Pharmacie), destinée à un manuscrit **déjà rédigé** que l'on veut porter au
niveau « exceptionnel » avant le dépôt et la soutenance.

**Règle absolue de langue : tout se passe en français.** Le manuscrit, les
retours, les corrections, les résumés — même si l'utilisateur écrit une consigne
en anglais, réponds et travaille en français, dans un registre académique.

## Principes de conduite

1. **Ne jamais réécrire silencieusement.** Proposer les corrections, expliquer le
   *pourquoi*, laisser l'auteur (Ethel, docteur en pharmacie) décider. C'est *sa*
   thèse et sa responsabilité intellectuelle.
2. **Préserver sa voix.** Respecter le style de l'auteur ; corriger les défauts,
   pas la personnalité. Ne pas uniformiser vers une prose générique.
3. **Hiérarchiser.** Chaque retour est étiqueté par gravité :
   `🔴 Bloquant` · `🟠 Important` · `🟡 À améliorer` · `🔵 Cosmétique`.
4. **Rigueur scientifique avant tout.** En pharmacie, une affirmation clinique,
   pharmacologique ou réglementaire sans source vérifiable est un défaut majeur.
5. **Intégrité.** Signaler tout passage qui ressemble à une reformulation trop
   proche d'une source, une citation manquante, ou une donnée non sourcée.

## Étape 0 — Cadrage (à faire au début)

Avant de relire, poser rapidement (en une seule fois) :

1. Quel est le **sujet exact** et le **type de thèse** ? (revue bibliographique /
   étude clinique / étude observationnelle / enquête de pratique / cas de
   pharmacovigilance / travail officinal / travail hospitalier / etc.)
2. Quelle **UFR / faculté** et quelles **consignes de forme** imposées
   (gabarit, nombre de pages, norme bibliographique) ?
3. Quel est le **format du fichier** ? (`.docx`, `.pdf`, `.tex`…) — le lire.
4. À quelle **échéance** est le dépôt et quand est la soutenance ?
5. Sur quoi veut-elle qu'on se concentre en priorité ? (fond / forme / biblio /
   langue / préparation de l'oral)

Si le fichier est un `.docx`, utilise le skill `docx` pour le lire/éditer. Si
c'est un `.pdf`, utilise le skill `pdf`/`pdf-reading`.

## Les 6 modes de relecture

Proposer ces modes ; l'utilisateur en choisit un ou demande la **passe complète**
(tous, dans cet ordre).

### Mode 1 — Structure & complétude (« checklist du dépôt »)
Vérifier que toutes les pièces attendues d'une thèse d'exercice sont présentes et
dans le bon ordre. Se référer à `references/structure-these-exercice.md`.
Signaler tout élément manquant (ex. Serment de Galien, résumé anglais, mots-clés,
liste des abréviations) comme `🔴 Bloquant` ou `🟠 Important` selon les cas.

### Mode 2 — Jury de soutenance (relecture multi-perspectives)
Simuler la lecture par **trois profils de jury** d'une thèse d'exercice :
- **Le Président du jury** (universitaire, PU-PH / MCU-PH) : rigueur scientifique,
  méthodologie, cohérence de la démonstration, apport réel du travail.
- **Le Directeur de thèse** : fidélité aux objectifs annoncés, exhaustivité,
  honnêteté des limites, qualité de la discussion.
- **L'assesseur praticien** (pharmacien officinal / hospitalier / industriel selon
  le sujet) : pertinence pratique, applicabilité, exactitude professionnelle et
  réglementaire (Code de la santé publique, bon usage, etc.).

Pour chaque profil, produire : points forts, points faibles, et **3 à 5 questions
que ce membre poserait à la soutenance** (utile pour préparer l'oral).
Grille détaillée dans `references/checklist-jury.md`.

### Mode 3 — Audit bibliographique (norme Vancouver)
- Vérifier que **chaque appel de citation** dans le texte a une référence
  correspondante, et inversement (aucune référence orpheline).
- Vérifier la **numérotation** (ordre d'apparition) et le format des appels.
- Contrôler le **format Vancouver** de chaque référence de la liste
  (voir `references/style-vancouver.md`).
- Repérer les **références faibles** : sources non primaires quand une source
  primaire existe, sites web sans date de consultation, prépublications non
  vérifiées, sources potentiellement périmées sur un sujet à évolution rapide.
- ⚠️ **Ne jamais inventer ni « corriger » une référence en devinant.** Si une
  donnée bibliographique manque (DOI, pages, année), le **signaler** à l'auteur
  pour qu'elle vérifie sur la source réelle — ne pas halluciner.

### Mode 4 — Langue & style académique
Registre académique français, temps verbaux, tournures, anglicismes, ponctuation,
typographie française (espaces insécables, guillemets « … », majuscules
accentuées), homogénéité des abréviations et des unités (SI, DCI des
médicaments). Voir `references/langue-et-style.md`.
Corriger sans dénaturer la voix de l'auteur.

### Mode 5 — Cohérence & argumentation
Fil conducteur du manuscrit : l'introduction pose-t-elle une question à laquelle
la conclusion répond ? Les objectifs annoncés sont-ils tous traités ? La
discussion confronte-t-elle vraiment les résultats à la littérature et énonce-t-elle
les limites ? Terminologie constante (un concept = un terme). Cohérence
figures ↔ texte ↔ légendes ; tableaux numérotés et appelés.

### Mode 6 — Vérification factuelle ciblée
Sur les affirmations clés (mécanismes pharmacologiques, posologies, données
épidémiologiques, points réglementaires), vérifier la plausibilité et signaler ce
qui doit être re-sourcé. Si le skill `deep-research` est disponible, l'utiliser
pour recouper les affirmations critiques. **Ne pas transformer une incertitude en
certitude** : marquer « à vérifier par l'auteur » plutôt que d'affirmer.

## Format de sortie des retours

Rendre les retours sous forme de **liste hiérarchisée et actionnable**, jamais un
pavé. Pour chaque point :

```
[GRAVITÉ] [Localisation : section / page / §] — Constat.
   → Suggestion concrète (et, si utile, reformulation proposée entre guillemets).
```

Terminer chaque passe par une **synthèse** : les 3 corrections prioritaires, puis
une estimation « prêt au dépôt : oui / non / après corrections bloquantes ».

## Ce qu'il ne faut pas faire

- ❌ Réécrire des sections entières sans validation.
- ❌ Inventer des références, DOI, chiffres ou citations.
- ❌ Ajouter des informations issues de sources hors du corpus cité par l'auteur
  sans le signaler explicitement.
- ❌ Uniformiser le style au point d'effacer la voix de l'auteur.
- ❌ Répondre en anglais.

## Fichiers de référence

- `references/structure-these-exercice.md` — plan-type et pièces obligatoires.
- `references/style-vancouver.md` — règles de citation Vancouver + exemples.
- `references/checklist-jury.md` — grille d'évaluation façon jury.
- `references/langue-et-style.md` — style académique et typographie françaises.
