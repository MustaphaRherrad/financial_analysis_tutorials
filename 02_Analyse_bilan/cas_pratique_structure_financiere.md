Voici un exemple complet de fichier `cas_pratique_structure_financiere.md`, présentant un cas pratique chiffré d’analyse de la structure financière d’une entreprise :

---

```markdown
# Cas pratique – Analyse de la structure financière

Ce cas pratique présente l’analyse de la structure financière de l’entreprise **TechNova**, spécialisée dans la fabrication de composants électroniques.

---

## 1. Données comptables

### Actif (en €)

| **Poste**                        | **Montant**    |
|----------------------------------|----------------|
| Immobilisations                  | 350 000        |
| Stocks                           | 80 000         |
| Créances clients                 | 120 000        |
| Disponibilités (trésorerie)      | 50 000         |
| **Total actif**                  | **600 000**    |

### Passif (en €)

| **Poste**                        | **Montant**    |
|----------------------------------|----------------|
| Capitaux propres                 | 200 000        |
| Dettes financières (LT)          | 150 000        |
| Dettes fournisseurs              | 100 000        |
| Dettes fiscales et sociales      | 50 000         |
| Découverts bancaires             | 100 000        |
| **Total passif**                 | **600 000**    |

---

## 2. Calcul des indicateurs financiers

### a. Fonds de Roulement Net Global (FRNG)



FRNG = Capitaux permanents – Actifs immobilisés
FRNG = (Capitaux propres + Dettes financières LT) – Immobilisations
FRNG = (200 000 + 150 000) – 350 000 = **0**



➡️ **FRNG nul** : aucune ressource longue disponible pour financer le cycle d’exploitation.

---

### b. Besoin en Fonds de Roulement (BFR)



BFR = Actifs circulants – Passifs circulants (hors dettes financières)
BFR = (Stocks + Créances clients) – (Fournisseurs + Dettes fiscales/sociales)
BFR = (80 000 + 120 000) – (100 000 + 50 000) = **50 000**



➡️ **BFR positif** : l’entreprise a un besoin permanent de 50 000 € pour financer son cycle court.

---

### c. Trésorerie nette (TN)



TN = FRNG – BFR = 0 – 50 000 = **–50 000**



➡️ **Trésorerie nette négative** : l’entreprise est en difficulté de liquidité.

---

## 3. Ratios de structure

| **Ratio**                   | **Formule**                                | **Calcul**                            | **Résultat** |
|-----------------------------|---------------------------------------------|----------------------------------------|--------------|
| Autonomie financière        | Capitaux propres / Total passif            | 200 000 / 600 000                      | **33 %**     |
| Gearing (levier financier)  | Dettes financières / Capitaux propres      | 150 000 / 200 000                      | **0,75**     |
| Solvabilité générale        | Capitaux propres / Total actif             | 200 000 / 600 000                      | **33 %**     |

---

## 4. Interprétation

- L’entreprise a une **autonomie correcte** mais qui devrait être renforcée.
- Le **gearing est raisonnable** (< 1), mais pourrait augmenter si les dettes court terme croissent.
- La **structure est tendue** car le FRNG est nul, le BFR positif et la trésorerie nette négative.

---

## 5. Recommandations

- **Renforcer les capitaux propres** via une augmentation de capital ou réinvestissement des bénéfices.
- **Réduire le BFR** : accélérer le recouvrement client, négocier des délais fournisseurs.
- **Améliorer la trésorerie** : rechercher des financements bancaires de court terme à moindre coût.

---

## Diagramme Mermaid – Synthèse du cas

```mermaid
graph TD
    A[Structure financière TechNova]
    A --> B1[Actifs]
    A --> B2[Passifs]
    B1 --> C1[Immobilisations: 350k]
    B1 --> C2[Stocks: 80k]
    B1 --> C3[Créances clients: 120k]
    B1 --> C4[Trésorerie: 50k]
    B2 --> D1[Capitaux propres: 200k]
    B2 --> D2[Dettes LT: 150k]
    B2 --> D3[Fournisseurs: 100k]
    B2 --> D4[Dettes fiscales: 50k]
    B2 --> D5[Découvert bancaire: 100k]
    
    A --> E[Calculs]
    E --> E1[FRNG = 0]
    E --> E2[BFR = 50k]
    E --> E3[Trésorerie nette = –50k]
    E --> E4[Autonomie: 33%]
    E --> E5[Gearing: 0,75]
