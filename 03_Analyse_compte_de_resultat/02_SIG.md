# Tutoriel : Le Solde Intermédiaire de Gestion (SIG)

## Introduction

Le **Solde Intermédiaire de Gestion (SIG)** est un outil d'analyse financière qui décompose le **compte de résultat** pour mieux comprendre la formation du résultat d’une entreprise. Il met en évidence plusieurs soldes successifs, chacun révélant une étape de la création de valeur.
Autrement dit, le SIG sert à découper les résultats d’une entreprise en plusieurs étapes, pour mieux comprendre comment elle gagne de l’argent et où elle en dépense. Cela aide à voir, étape par étape, comment se forme le bénéfice. On dit ici qu'on procède par "cascade".

---

## 1. Objectifs des SIG

- Comprendre la performance opérationnelle.
- Identifier les marges et les excédents à chaque étape de gestion.
- Mieux piloter l’entreprise à travers des indicateurs économiques.
- Comparer avec des entreprises du même secteur.

---

## 2. Les principaux SIG à connaître

### 1. Marge commerciale
**Formule** : Ventes de marchandises – Coût d’achat des marchandises vendues  
➡️ Utilisé pour les entreprises commerciales.

---

### 2. Production de l’exercice
**Formule** : Production vendue + Production stockée + Production immobilisée  
➡️ Indique la valeur ajoutée par l’activité de production.

---

### 3. Valeur ajoutée (VA)
**Formule** : Marge commerciale + Production de l’exercice – Consommations externes  
➡️ Mesure la richesse créée par l’entreprise à partir de ses activités.

---

### 4. Excédent Brut d’Exploitation (EBE)
**Formule** : Valeur ajoutée – Charges de personnel – Impôts et taxes  
➡️ Reflète la performance de l’exploitation, sans tenir compte de la politique d’amortissement ni de financement.

---

### 5. Résultat d’exploitation
**Formule** : EBE + Autres produits d’exploitation – Dotations aux amortissements et provisions  
➡️ Tient compte des dotations et des reprises, mais pas encore du résultat financier.

---

### 6. Résultat courant avant impôts (RCAI)
**Formule** : Résultat d’exploitation + Résultat financier  
➡️ Intègre les charges et produits financiers (intérêts, placements…).

---

### 7. Résultat exceptionnel
**Formule** : Produits exceptionnels – Charges exceptionnelles  
➡️ Événements inhabituels ou non récurrents.

---

### 8. Résultat net comptable
**Formule** : RCAI + Résultat exceptionnel – Impôt sur les bénéfices  
➡️ Dernier niveau de résultat, celui qui figure au bilan.

---

## 3. Tableau récapitulatif des SIG

| Solde intermédiaire               | Formule simplifiée                                            | Ce qu’il indique                                      |
|----------------------------------|---------------------------------------------------------------|-------------------------------------------------------|
| Marge commerciale                | Ventes – Achats revendus                                      | Rentabilité brute d’une activité commerciale          |
| Production de l’exercice         | Prod. vendue + stockée + immobilisée                          | Activité de production                               |
| Valeur ajoutée                   | Marge + Production – Consommations externes                   | Création de richesse propre                          |
| Excédent Brut d’Exploitation     | VA – Charges personnel – Impôts & taxes                       | Rentabilité opérationnelle brute                     |
| Résultat d’exploitation          | EBE + Autres produits – Dotations amort. & provisions         | Résultat purement industriel                         |
| Résultat courant avant impôts    | Résultat d’exploitation + Résultat financier                  | Résultat avant impôts et éléments exceptionnels       |
| Résultat exceptionnel            | Produits – Charges exceptionnels                              | Événements non récurrents                            |
| Résultat net                     | RCAI + Résultat exceptionnel – Impôts                         | Bénéfice ou perte final(e)                           |

---
## 4. Cas pratique de calcul des SIG
👉 [Exemple_pratique](./cas_pratique_SIG.md)

---

## 5. Diagramme Mermaid – Construction des SIG

```mermaid
graph TB
    %% Niveau 1 - Marge commerciale
    A[Ventes de marchandises] --> C[Marge commerciale]
    B[Achat de marchandises vendues] --> C

    %% Niveau 1 - Production
    D[Production vendue] --> G[Production de l'exercice]
    E[Production stockée] --> G
    F[Production immobilisée] --> G

    %% Niveau 2 - Valeur ajoutée
    C --> I[Valeur ajoutée]
    G --> I
    H[Consommations externes] --> I

    %% Niveau 3 - EBE
    I --> L[EBE]
    J[Charges de personnel] --> L
    K[Impôts et taxes] --> L

    %% Niveau 4 - Résultat d'exploitation
    L --> O[Résultat d'exploitation]
    M[Autres produits d'exploitation] --> O
    N[Dotations aux amortissements] --> O

    %% Niveau 5 - Résultat courant
    O --> R[RCAI]
    P[Produits financiers] --> R
    Q[Charges financières] --> R

    %% Niveau 6 - Résultat exceptionnel
    S[Produits exceptionnels] --> U[Résultat exceptionnel]
    T[Charges exceptionnelles] --> U

    %% Niveau 7 - Résultat final
    R --> W[Résultat net comptable]
    U --> W
    V[Impôt sur les bénéfices] --> W

    %% Style des noeuds
    style C fill:#e6f3ff,stroke:#333
    style G fill:#e6f3ff,stroke:#333
    style I fill:#e6ffe6,stroke:#333
    style L fill:#fff2cc,stroke:#333
    style O fill:#ffe6cc,stroke:#333
    style R fill:#f0f0f0,stroke:#333,stroke-width:2px
    style U fill:#f0f0f0,stroke:#333
    style W fill:#e6ffe6,stroke:#333,stroke-width:2px

    %% Légende implicite par couleur
    classDef produits fill:#e6f3ff,stroke:#333;
    classDef indicateurs fill:#e6ffe6,stroke:#333;
    classDef intermediaires fill:#fff2cc,stroke:#333;
    classDef resultats fill:#ffe6cc,stroke:#333;
    classDef final fill:#e6ffe6,stroke-width:2px;

    class A,B,D,E,F,H,J,K,M,N,P,Q,S,T,V produits;
    class I indicateurs;
    class L intermediaires;
    class O,R resultats;
    class W final;
```

---
## Prochain tuto

👉 [Les Ratios de Rentabilité et la Capacité d'autofinancement](./03_ratios_rentabilite_et_CAF.md)
