# 🚀 Structures de Données et Algorithmes (DSA) - Guide d'Étude

<div align="center">

**Un répertoire couvrant les concepts fondamentaux et avancés en structures de données et algorithmes**

</div>


---

## 📋 Table des matières

- [Aperçu](#aperçu)
- [Structure du répertoire](#structure-du-répertoire)
- [Sujets principaux](#sujets-principaux)
- [Démarrage](#démarrage)
- [Concepts clés par module](#concepts-clés-par-module)
- [Référence rapide](#référence-rapide)
- [Contribuer](#contribuer)
- [Licence](#licence)

---

## Aperçu

Ce repo est une **ressource d'étude** pour maîtriser les structures de données et les algorithmes.
---

## Structure du répertoire

```
DSA/
├── README.md (ce fichier)
├── INDEX.md (index rapide)
├── 1_Fondations_POO/               [Fondations de la POO]
├── 2_Structures_Lineaires/         [Structures de données linéaires]
├── 3_Hashage/                      [Hachage et tables de hachage]
├── 4_Algorithmes_Tri/              [Algorithmes de tri]
├── 5_Arbres_Recherche/             [Arbres de recherche]
├── 6_Arbres_Equilibres/            [Arbres équilibrés]
├── 7_Monceaux/                     [Monceaux et files de priorité]
├── 8_Graphes/                      [Graphes et algorithmes sur graphes]
├── 9_Recherche_Patron_PD/          [Recherche de patron et programmation dynamique]
└── 10_Ensembles_Disjoints/         [Ensembles disjoints / Union-Find]
```

---

## Sujets principaux

### 1️⃣ **Fondations de la programmation orientée objet**
📂 [1_Fondations_POO/](1_Fondations_POO/README.md)

Maîtrisez les éléments constitutifs de la POO avec Java :
- Classes et objets (attributs, méthodes, constructeurs)
- Encapsulation et modificateurs d'accès
- Héritage et composition
- Interfaces et polymorphisme
- Réutilisation et organisation du code

---

### 2️⃣ **Structures de données linéaires**
📂 [2_Structures_Lineaires/](2_Structures_Lineaires/README.md)

Collections ordonnées essentielles et structures LIFO/FIFO :
- **Listes :** ArrayList, LinkedList, implémentations basées sur tableaux
- **Piles :** Principe LIFO, applications
- **Files :** Principe FIFO, files circulaires
- Interfaces : Collection, Iterable, List
- Analyse de complexité temporelle/spatiale

---

### 3️⃣ **Hachage et tables de hachage**
📂 [3_Hashage/](3_Hashage/README.md)

Récupération rapide de données par des fonctions de hachage :
- Fonctions de hachage et méthodes de dispersement
- Stratégies de résolution de collisions (chaînage, adressage ouvert, double hachage)
- Rehachage et facteurs de charge
- Implémentations HashMap/HashSet
- Optimisation des performances

---

### 4️⃣ **Algorithmes de tri**
📂 [4_Algorithmes_Tri/](4_Algorithmes_Tri/README.md)

Étude complète des techniques de tri avec analyse de complexité :
- Tris simples : Sélection, Bulle, Insertion (O(n²))
- Tris avancés : Fusion, QuickSort, TriParTas (O(n log n))
- Stabilité et tris sur place
- Tri par comptage (temps linéaire)
- Comparaison d'algorithmes et critères de sélection

---

### 5️⃣ **Arbres de recherche**
📂 [5_Arbres_Recherche/](5_Arbres_Recherche/README.md)

Organisation hiérarchique des données et recherche efficace :
- Arbres binaires et propriétés des arbres
- Parcours d'arbres (in-ordre, pré-ordre, post-ordre, niveau par niveau)
- Opérations sur arbres de recherche binaire (ABR)
- Recherche, insertion, suppression avec analyse de complexité

---

### 6️⃣ **Arbres équilibrés**
📂 [6_Arbres_Equilibres/](6_Arbres_Equilibres/README.md)

Maintenir les performances O(log n) avec des structures auto-équilibrantes :
- Arbres AVL (équilibrés en hauteur, rotations)
- Arbres Splay (optimisation d'accès par étalage)
- Algorithmes de maintien de l'équilibre
- Opérations logarithmiques garanties

---

### 7️⃣ **Monceaux et files de priorité**
📂 [7_Monceaux/](7_Monceaux/README.md)

Récupération efficace de données basée sur la priorité :
- Structures de tas minimum et maximum
- Propriétés et invariants des monceaux
- Opérations d'insertion, suppression et fusion
- Algorithme de tri par tas
- Implémentations des files de priorité

---

### 8️⃣ **Graphes et algorithmes sur graphes**
📂 [8_Graphes/](8_Graphes/README.md)

Représentations de réseaux et techniques algorithmiques avancées :
- Représentations de graphes (matrice d'adjacence, liste d'adjacence)
- Parcours de graphes : BFS (Parcours en largeur), DFS (Parcours en profondeur)
- Connexité et composantes connexes
- Algorithme de plus court chemin : Dijkstra
- Arbres couvrants minimaux (Kruskal, algorithme de Prim)
- Tri topologique

---

### 9️⃣ **Recherche de patron et programmation dynamique**
📂 [9_Recherche_Patron_PD/](9_Recherche_Patron_PD/README.md)

Appariement de chaînes et optimisation par mémorisation :
- Algorithmes d'appariement de chaînes : Naïf, KMP, Rabin-Karp
- Approche par automate d'états finis (AEF)
- Introduction à la programmation dynamique
- Plus longue sous-séquence commune (PLSC)
- Chaînage optimal de matrices
- Sous-structure optimale et mémorisation

---

### 🔟 **Ensembles disjoints (Union-Find)**
📂 [10_Ensembles_Disjoints/](10_Ensembles_Disjoints/README.md)

Gestion efficace d'ensembles partitionnés avec opérations d'union et de recherche :
- Structure de données Union-Find (Structure d'ensemble disjoint)
- Optimisations : compression de chemin et union par rang
- Opérations en temps quasi-constant (O(1) amorti)
- Applications : détection de cycle, algorithme de Kruskal, génération de labyrinthes
- Problèmes de connectivité de graphes

---

## Concepts clés par module

### Référence rapide d'analyse de complexité

| Structure de données | Insertion | Recherche | Suppression | Espace |
|---|---|---|---|---|
| Tableau | O(n) | O(n) | O(n) | O(n) |
| Tableau trié | O(n) | O(log n) | O(n) | O(n) |
| Liste chaînée | O(1)* | O(n) | O(1)* | O(n) |
| Table de hachage | O(1)† | O(1)† | O(1)† | O(n) |
| ABR (équilibré) | O(log n) | O(log n) | O(log n) | O(n) |
| ABR (déséquilibré) | O(n) | O(n) | O(n) | O(n) |
| Arbre AVL | O(log n) | O(log n) | O(log n) | O(n) |
| Tas minimum | O(log n) | O(1) | O(log n) | O(n) |

*avec référence au point d'insertion/suppression  
†cas moyen, en supposant une bonne fonction de hachage

### Algorithmes de tri en un coup d'œil

| Algorithme | Meilleur | Moyen | Pire | Espace | Stable |
|---|---|---|---|---|---|
| Tri par sélection | O(n²) | O(n²) | O(n²) | O(1) | Non |
| Tri à bulles | O(n) | O(n²) | O(n²) | O(1) | Oui |
| Tri par insertion | O(n) | O(n²) | O(n²) | O(1) | Oui |
| Tri par fusion | O(n log n) | O(n log n) | O(n log n) | O(n) | Oui |
| QuickSort | O(n log n) | O(n log n) | O(n²) | O(log n) | Non |
| Tri par tas | O(n log n) | O(n log n) | O(n log n) | O(1) | Non |
| Tri par comptage | O(n+k) | O(n+k) | O(n+k) | O(k) | Oui |

---

## Référence rapide

### Algorithmes à connaître absolument

**Algorithmes sur graphes :** ([Module 8](8_Graphes/README.md))
- [BFS, DFS](8_Graphes/8.2_Parcours_Connexite.md) (parcours, détection de cycles)
- [Dijkstra](8_Graphes/8.3_Algorithmes_Chemin_Ordre.md) (chemin le plus court, une source)
- [Kruskal, Prim](8_Graphes/8.4_Arbres_Sous_Tendant_Minimum.md) (arbre couvrant minimal)
- [Tri topologique](8_Graphes/8.3_Algorithmes_Chemin_Ordre.md) (ordonnancement DAG)

**Programmation dynamique :** ([Module 9](9_Recherche_Patron_PD/README.md))
- [Plus longue sous-séquence commune (PLSC)](9_Recherche_Patron_PD/9.2_Programmation_Dynamique.md)
- [Chaînage optimal de matrices](9_Recherche_Patron_PD/9.2_Programmation_Dynamique.md)
- [Problème du sac à dos 0/1](9_Recherche_Patron_PD/9.2_Programmation_Dynamique.md)

**Appariement de chaînes :** ([Module 9](9_Recherche_Patron_PD/README.md))
- [Recherche naïve](9_Recherche_Patron_PD/9.1_Recherche_Patron.md)
- [Rabin-Karp (hachage roulant)](9_Recherche_Patron_PD/9.1_Recherche_Patron.md)
- [Automate d'états finis (AEF)](9_Recherche_Patron_PD/9.1_Recherche_Patron.md)

**Opérations sur structures de données :**
- [Union-Find avec compression de chemin et union par rang](10_Ensembles_Disjoints/README.md) (Module 10)
- [Insertion et extraction dans les tas](7_Monceaux/README.md) (Module 7)
- [Rotations dans les arbres AVL](6_Arbres_Equilibres/README.md) (Module 6)

---