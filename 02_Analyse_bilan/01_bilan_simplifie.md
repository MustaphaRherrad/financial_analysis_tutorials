# 📊 Bilan Simplifié : Définition, Structure et Illustration

Le **bilan comptable** est une photographie de la situation financière d’une entreprise à un instant donné (souvent à la fin d’un exercice comptable). Il présente ce que possède l’entreprise (**actif**) et ce qu’elle doit (**passif**), et permet d'évaluer la **structure financière** et la **solvabilité** de l’entreprise.

---

## 🧱 Structure générale du bilan

Le bilan est divisé en deux grandes parties :

| Élément        | Description |
|----------------|-------------|
| **Actif**      | Ce que possède l’entreprise, classé en fonction de la liquidité (facilité à se transformer en argent liquide). |
| **Passif**     | Ce que l’entreprise doit, classé par exigibilité (ordre dans lequel les dettes doivent être remboursées). |

---

## 🧾 Détail des postes du bilan simplifié

### **ACTIF**

| Poste                     | Définition |
|---------------------------|------------|
| **Actif immobilisé**      | Biens durables utilisés dans l’activité (machines, brevets, bâtiments). |
| **Actif circulant**       | Biens à court terme destinés à être transformés ou consommés (stocks, créances clients). |
| **Trésorerie active**     | Disponibilités en caisse ou en banque. |

### **PASSIF**

| Poste                     | Définition |
|---------------------------|------------|
| **Capitaux propres**      | Apports des associés, réserves, résultat de l'exercice. C'est ce que l’entreprise possède en propre. |
| **Dettes à long terme**   | Emprunts bancaires et dettes financières exigibles à plus d’un an. |
| **Dettes à court terme**  | Fournisseurs, charges sociales, dettes fiscales, exigibles à court terme. |
| **Trésorerie passive**    | Découverts bancaires ou lignes de crédit à court terme. |

---

## 📋 Exemple de tableau de bilan simplifié (en euros)

| **ACTIF**                        | Montant (€) | **PASSIF**                      | Montant (€) |
|----------------------------------|-------------|----------------------------------|-------------|
| Immobilisations corporelles      | 150 000     | Capital social                   | 100 000     |
| Immobilisations incorporelles    | 20 000      | Réserves                         | 30 000      |
| Stocks                           | 25 000      | Résultat de l'exercice           | 10 000      |
| Créances clients                 | 35 000      | Dettes à long terme              | 60 000      |
| Trésorerie active                | 15 000      | Dettes fournisseurs              | 25 000      |
|                                  |             | Dettes fiscales et sociales      | 15 000      |
|                                  |             | Trésorerie passive (découvert)   | 5 000       |
| **Total Actif**                  | **245 000** | **Total Passif**                 | **245 000** |

---

## 🧩 Représentation visuelle en Mermaid

```mermaid
flowchart TB
    A[ACTIF] --> A1[Immobilisations<br>corporelles et incorporelles]
    A --> A2[Actif circulant<br>stocks, créances]
    A --> A3[Trésorerie active]

    B[PASSIF] --> B1[Capitaux propres<br>capital, réserves, résultat]
    B --> B2[Dettes à long terme]
    B --> B3[Dettes à court terme]
    B --> B4[Trésorerie passive]

    A -. équilibre .-> B

    