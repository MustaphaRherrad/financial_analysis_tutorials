# 03 – Structure financière de l'entreprise

La structure financière décrit **comment une entreprise est financée**, c’est-à-dire la répartition entre **capitaux propres** et **dettes**. Elle reflète sa solidité à long terme et sa capacité à résister à des chocs économiques.

---

## 1. Composantes de la structure financière

| **Poste**                         | **Définition**                                                                 |
|----------------------------------|--------------------------------------------------------------------------------|
| **Capitaux propres**             | Apports des associés, bénéfices non distribués, réserves                      |
| **Dettes financières**           | Emprunts bancaires, obligations, crédits-bails                                |
| **Passif circulant**             | Dettes à court terme (fournisseurs, URSSAF, TVA, etc.)                        |
| **Total du passif**              | Capitaux propres + Dettes (long et court terme)                               |

---

## 2. Équilibre financier

Un bon équilibre suppose que :

- Les **actifs longs** (immobilisations) soient financés par des **ressources longues** (capitaux propres + dettes à long terme).
- Les actifs courts (stocks, créances) soient couverts par des passifs à court terme (dettes fournisseurs, etc.).

---

## 3. Indicateurs clés

| **Indicateur**                  | **Formule**                                                | **Interprétation**                                 |
|--------------------------------|-------------------------------------------------------------|----------------------------------------------------|
| **Autonomie financière**       | Capitaux propres / Total passif                            | Plus le ratio est élevé, plus l’entreprise est stable |
| **Gearing (levier financier)** | Dettes financières / Capitaux propres                      | Montre la dépendance aux emprunts                   |
| **Ratio de solvabilité**       | Capitaux propres / Total actif                             | Capacité à faire face à ses obligations             |
| **Fonds de roulement net (FRNG)** | Capitaux permanents – Actif immobilisé                    | Ressources longues restant pour financer le cycle court |
| **Besoin en fonds de roulement (BFR)** | Actif circulant – Passif circulant                      | Besoin ou surplus de trésorerie                     |
| **Trésorerie nette**           | FRNG – BFR                                                 | Niveau de liquidités disponible                     |

---

## 4. Analyse de la structure financière

### Scénarios fréquents

- **Structure équilibrée** : FRNG > BFR → Trésorerie positive
- **Structure tendue** : FRNG ≈ BFR → Trésorerie fragile
- **Structure déséquilibrée** : FRNG < BFR → Trésorerie négative

### Effets d’une mauvaise structure

- Difficultés de financement à court terme
- Risques accrus de cessation de paiement
- Dépendance excessive aux créanciers

---

## 5. Amélioration de la structure

- **Augmenter les capitaux propres** (apports, bénéfices non distribués)
- **Renégocier les dettes** à long terme
- **Maîtriser le BFR** (optimisation des stocks, relances clients)
- **Diminuer les investissements non essentiels**

---
## 4. Cas pratique de calcul des SIG
👉 [Exemple_pratique](./cas_pratique_structure_financiere.md)

## Tableau récapitulatif

| Élément clé                  | Bonne pratique                          | Signal d’alerte                        |
|-----------------------------|------------------------------------------|----------------------------------------|
| Capitaux propres            | > 40 % du total passif                   | < 20 % → Faible autonomie              |
| Gearing                     | < 1                                      | > 2 → Trop de dettes                   |
| FRNG                        | Positif                                  | Négatif → structure déséquilibrée     |
| BFR                         | Stable ou prévisible                     | Volatil → manque de pilotage           |
| Trésorerie nette            | Positive                                 | Déficit chronique → alerte rouge       |

---

## Diagramme Mermaid – Structure financière

```mermaid
flowchart TD
    A[Structure Financière de l'entreprise]
    A --> B[Capitaux Propres]
    A --> C[Dettes financières]
    A --> D[Passif circulant]
    B --> B1[Apports + Réserves + Résultat]
    C --> C1[Emprunts bancaires, crédits-bails]
    D --> D1[Dettes fournisseurs, fiscales, sociales]
    
    A --> E[Indicateurs]
    E --> E1[Autonomie financière]
    E --> E2[Gearing]
    E --> E3[Solvabilité]
    E --> E4[Fonds de roulement (FRNG)]
    E --> E5[BFR]
    E --> E6[Trésorerie nette]
```

---
## Prochain chapitre

👉 [Etude de cas: Ratios Bilan](./05_cas_pratique_ratios.md)
