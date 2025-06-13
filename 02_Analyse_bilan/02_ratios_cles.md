# 02 – Ratios clés d’analyse financière

Les ratios financiers permettent d’analyser la performance, la rentabilité, la structure financière et la liquidité d’une entreprise. Ils constituent des indicateurs synthétiques et comparables dans le temps ou entre entreprises.

---

## 1. Ratios de rentabilité

### Rentabilité économique (RE)
- **Formule** : Résultat d’exploitation / Capitaux engagés
- **Signification** : Capacité de l’entreprise à générer un résultat d’exploitation à partir de ses investissements.

### Rentabilité financière (RF)
- **Formule** : Résultat net / Capitaux propres
- **Signification** : Capacité de l’entreprise à rémunérer ses actionnaires.

---

## 2. Ratios de structure financière

### Autonomie financière
- **Formule** : Capitaux propres / Total bilan
- **Signification** : Indique le niveau d’indépendance financière de l’entreprise vis-à-vis de ses dettes.

### Endettement global
- **Formule** : Dettes financières / Capitaux propres
- **Signification** : Évalue le niveau de recours à l’endettement.

---

## 3. Ratios de liquidité

### Liquidité générale
- **Formule** : Actif circulant / Passif circulant
- **Interprétation** : >1 : l’entreprise peut faire face à ses dettes à court terme.

### Liquidité réduite
- **Formule** : (Actif circulant – Stocks) / Passif circulant
- **Interprétation** : Mesure plus stricte de la solvabilité à court terme.

---

## 4. Ratios d'activité

### Rotation des stocks
- **Formule** : Coût des ventes / Stock moyen
- **Signification** : Nombre de fois que le stock est renouvelé dans l’année.

### Délai moyen de paiement clients
- **Formule** : (Créances clients / Chiffre d’affaires TTC) × 360
- **Signification** : Temps moyen que mettent les clients à régler leurs factures.

### Délai moyen de paiement fournisseurs
- **Formule** : (Dettes fournisseurs / Achats TTC) × 360
- **Signification** : Temps moyen que met l’entreprise pour payer ses fournisseurs.

---

## Tableau récapitulatif des ratios clés

| **Catégorie**        | **Ratio**                        | **Formule simplifiée**                              | **Objectif/interprétation**                  |
|----------------------|----------------------------------|-----------------------------------------------------|----------------------------------------------|
| Rentabilité          | Rentabilité économique           | Résultat Exploitation / Capitaux engagés            | Efficacité des investissements               |
| Rentabilité          | Rentabilité financière           | Résultat net / Capitaux propres                     | Rémunération des actionnaires                |
| Structure financière | Autonomie financière             | Capitaux propres / Total bilan                      | Solidité de la structure                     |
| Structure financière | Endettement global               | Dettes financières / Capitaux propres               | Niveau de risque financier                   |
| Liquidité            | Liquidité générale               | Actif circulant / Passif circulant                  | Solvabilité à court terme                    |
| Liquidité            | Liquidité réduite                | (Actif circulant – Stocks) / Passif circulant       | Solvabilité immédiate                        |
| Activité             | Rotation des stocks              | Coût des ventes / Stock moyen                       | Rapidité du cycle d’écoulement               |
| Activité             | Délai paiement clients           | (Créances / CA TTC) × 360                           | Moyenne des encaissements clients            |
| Activité             | Délai paiement fournisseurs      | (Dettes / Achats TTC) × 360                         | Moyenne des règlements fournisseurs          |

---
##  Cas pratique de calcul des SIG
👉 [Exemple_pratique](./cas_pratique_ratios.md)

## Diagramme Mermaid – Classification des ratios

```mermaid
graph TB
    A[Ratios financiers] --> B[Rentabilité]
    A --> C[Structure financière]
    A --> D[Liquidité]
    A --> E[Activité]

    B --> B1[Rentabilité économique]
    B --> B2[Rentabilité financière]

    C --> C1[Autonomie financière]
    C --> C2[Endettement global]

    D --> D1[Liquidité générale]
    D --> D2[Liquidité réduite]

    E --> E1[Rotation des stocks]
    E --> E2[Délai paiement clients]
    E --> E3[Délai paiement fournisseurs]

