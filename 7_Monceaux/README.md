# 7. Monceaux (Heaps)

Cette section couvre les structures de tas pour recherche efficace d'extrêmes.

## Concepts clés

- Propriété de monceau (min ou max)
- Implémentation par tableau
- Opérations : insertion, suppression du min
- Tri par monceau

## Important : Heap DSA vs Heap OS

⚠️ **Ne pas confondre !**

### Heap en DSA (ici)
- **Structure de données** : arbre binaire pour trouver min/max rapidement
- **Localité** : éléments en mémoire **adjacents** (tableau)
- **Objectif** : O(log N) pour accéder au minimum/maximum
- **Exemple** : `[9, 7, 6, 3, 2, 5, 1]` en array continu

### Heap en Système d'exploitation (OS)
- **Zone mémoire dynamique** : région de RAM destinée à l'allocation mémoire
- **Localisation** : commence aux adresses **basses de la RAM** (après le code et données statiques)
- **Objectif** : permettre aux programmes d'allouer/libérer mémoire à l'exécution
- **Exemple** : `malloc()` en C, `new` en Java
- **Gestion** : géré par l'OS (allocateur mémoire)

### Stack vs Heap (OS)

```
Mémoire RAM (typiquement) :
┌─────────────────────┐ Adresses hautes (0xFFFFFFFF)
│                     │
│   Stack (local)     │ ← Croît vers le bas
│   Pointers          │
│                     │
├─────────────────────┤
│                     │
│   Heap (dynamique)  │ ← Croît vers le haut
│   malloc(), new     │
│                     │
├─────────────────────┤
│   Données statiques │
│   (globales)        │
├─────────────────────┤
│   Code du programme │
└─────────────────────┘ Adresses basses (0x00000000)
```

**Collision possible** : Si Stack et Heap se rencontrent → **Crash du programme** (stack overflow ou heap overflow)

## Sous-sections

1. [7.1 Définition et Implémentation](7.1_Definition_Implementation.md)
2. [7.2 Opérations et Complexité](7.2_Operations_Complexite.md)
3. [7.3 Construction et Tri](7.3_Construction_Tri.md)

---

**[← Retour à l'index](../INDEX.md)**
