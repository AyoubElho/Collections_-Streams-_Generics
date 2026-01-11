
## I. Collections & Streams

### 1. Manipulation d'une List de produits

**Problème** :  
Créer une application permettant de gérer une liste de produits (ajout, suppression, modification, affichage, recherche par nom).

**Solution implémentée** :
- Classe `Product` (id: long, name: String, price: double)
- Utilisation d'`ArrayList<Product>`
- Opérations CRUD de base + recherche par nom (saisie utilisateur)

**Exécution** :
<img width="1167" height="740" alt="image" src="https://github.com/user-attachments/assets/17f0a17e-f566-4460-8588-9e85f4158d6b" />
### 2. Gestion des notes avec HashMap

**Problème** :  
Gérer les notes d'étudiants (clé = nom, valeur = note) avec plusieurs opérations statistiques.

**Solution** :
- `HashMap<String, Double>`
- Opérations : ajout/modification, suppression, taille, moyenne/min/max, présence de 20/20
- Affichage après chaque opération avec `forEach` + lambda

**Exemple d'exécution** :
<img width="1172" height="756" alt="image" src="https://github.com/user-attachments/assets/2eddaf22-d157-4ea8-83e9-3d208dd7b1ef" />
### 3. Ensembles (HashSet) – Groupes d'étudiants

**Problème** :  
Gérer deux groupes d'étudiants et afficher leur intersection + union.

**Solution** :
- Deux `HashSet<String>`
- Méthodes `retainAll()` pour intersection
- `addAll()` pour union

**Exemple** :
<img width="1194" height="409" alt="image" src="https://github.com/user-attachments/assets/710e3987-5c13-45e0-8db8-7e488e69409c" />

## II. Generics

### 1. Classe générique `GenericStorage<T>`

**Problème** :  
Créer une classe générique capable de stocker n'importe quel type d'objets.

**Solution** :

**************************************************
           GESTION DES PRODUITS -
**************************************************
1. Afficher tous les produits
2. Rechercher un produit par id
3. Ajouter un nouveau produit
4. Supprimer un produit (par id)
5. Quitter
→ Votre choix :

<img width="1180" height="873" alt="image" src="https://github.com/user-attachments/assets/1999f344-be1d-43b2-9ec0-96f6bf839e66" />
<img width="1181" height="635" alt="image" src="https://github.com/user-attachments/assets/6a79a029-6e06-410d-aea7-836286ed5ca0" />


