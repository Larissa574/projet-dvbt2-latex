# Reproduction LaTeX d'un article IEEE — DVB-T2

**Article à reproduire :** *Optimal M-QAM rotated constellation angle in DVB-T2*

**Équipe :** 4 membres · **Classe :** IEEEtran (conference) · **Outils :** GitHub et Overleaf

> Le dépôt contient pour le moment la structure de travail, et non la reproduction intégrale. Le PDF de l'article original est nécessaire pour recopier fidèlement le contenu.

## Répartition

| Responsable | Fichiers | Contenu |
|---|---|---|
| Personne 1 | `main.tex`, `sections/01_intro.tex` | Titre, auteurs, affiliations, résumé, mots-clés, Section I |
| Personne 2 | `sections/02_theory.tex` | Sections II-A, II-B, II-C et Figure 1 |
| Personne 3 | `sections/03_algorithm.tex` | Sections III-A, III-B, III-C, équations (1) à (16), Tableau I, Figures 2 et 3 |
| Personne 4 | `sections/04_results.tex`, `references.bib` | Sections IV, V, VI, remerciements, Tableaux II–IV, Figures 4–5, 18 références |

## Structure

```text
projet-dvbt2-latex/
├── main.tex
├── references.bib
├── sections/
│   ├── 01_intro.tex
│   ├── 02_theory.tex
│   ├── 03_algorithm.tex
│   └── 04_results.tex
├── images/
│   └── README.md
├── .gitignore
└── README.md
```

## Compiler

Importer le dépôt dans Overleaf (ou téléverser son contenu) et choisir `main.tex` comme document principal. Compiler avec **pdfLaTeX**. Bibliographie : BibTeX, style `IEEEtran`.

## Collaboration

1. Chaque membre crée une branche personnelle.
2. Il ne modifie que son fichier attitré ; la personne 1 gère `main.tex`, la personne 4 gère `references.bib`.
3. Les figures sont placées dans `images/`.
4. Toute clé `\cite{...}` doit être coordonnée avec la personne 4.
5. Chaque membre ouvre une Pull Request pour faire intégrer sa partie.
6. Avant chaque fusion, vérifier la compilation et la fidélité du contenu au document original.

## Vérifications finales

- En-tête, résumé et mots-clés identiques à l'article.
- Titres, texte, équations (1–16), tableaux (I–IV), figures (1–5) et légendes fidèles.
- Citations et 18 références exactes.
- Pagination et mise en page IEEE à comparer visuellement à l'original.
