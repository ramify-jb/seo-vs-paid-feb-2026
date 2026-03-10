# SEO vs Paid -- Engagement & Conversions

Analyse comparative SEO vs Paid pour les articles Ramify (fevrier 2026).

**Dashboard:** https://ramify-jb.github.io/seo-vs-paid-feb-2026/

## Donnees

Les fichiers CSV dans `data/` proviennent d'Ahrefs Web Analytics, filtres par canal (SEO organique vs Paid).

| Fichier | Contenu |
|---------|---------|
| `toppages-paid.csv` | Top pages Paid -- visitors, bounce rate, time on page |
| `toppages-seo.csv` | Top pages SEO -- visitors, bounce rate, time on page |
| `entrypages-paid.csv` | Entry pages Paid -- visitors ayant declenche un evenement, nombre d'evenements, duree de visite |
| `entrypages-seo.csv` | Entry pages SEO -- idem |

## Definition des conversions

Apres avoir atterri sur un article, le visiteur a navigate vers :
- Une **page cle** (offres, produits, tarifs...)
- Une **page produit**
- La **page contact**
- La **page d'inscription**

Note : certains evenements sont double-comptes entre categories (ex: la page contact est aussi une page cle). Cela n'affecte pas l'analyse comparative.

## Taux de conversion

`CR = visiteurs ayant declenche un evenement / visiteurs totaux de la page`

Les visiteurs totaux proviennent des fichiers `toppages-*.csv`, les visiteurs convertis des fichiers `entrypages-*.csv`.
