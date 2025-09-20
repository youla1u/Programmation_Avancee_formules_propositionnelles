# TP Algorithmique & Programmation – Logique Propositionnelle
Université de Lorraine – FST  
Cours de Jean Lieber (IMSD)  
Dernière version du sujet : 16 août 2019  

---

## 🎯 Objectifs
- Manipuler des **arbres d’expressions logiques**.
- Mettre en pratique la **programmation orientée objet** en Python :
  - Encapsulation
  - Héritage
  - Polymorphisme
- Explorer la **logique propositionnelle** et ses applications algorithmiques :
  - Tables de vérité
  - Satisfiabilité
  - Tautologies
  - Conséquence et équivalence logiques
  - Bases de connaissances

---

## 📚 Contenu
- **Fichiers Python fournis** :
  - Classes pour représenter des formules propositionnelles.
  - Parseur de chaînes de caractères en formules.
  - Générateur de tables de vérité.

- **Méthodes principales** :
  - `str_prefixe()` → affichage préfixé des formules.
  - `Parseur.exec()` → transformation d’une chaîne en formule.
  - `table_verite()` → génération automatique de la table de vérité.

---

## 🧩 Exercices
1. Représentation et affichage de formules.
2. Comptage des interprétations satisfaisantes.
3. Vérification de la **satisfiabilité**.
4. Test de **tautologie**.
5. Implémentation de **conséquence logique** (ϕ |= ψ) et **équivalence** (ϕ ≡ ψ).
6. Implémentation d’une **base de connaissances** et test d’inférence.
7. Étude de cas : mammifères ovipares (échidnés, ornithorynques, Toto).
8. Substitution de variables dans une formule.
9. Implémentation d’un algorithme **Davis-Putnam** (test de satisfiabilité).
10. Optimisation par **ordre des variables**.
11. Transformation en **forme normale disjonctive (FND/DNF)**.
12. Vérification de satisfiabilité via la FND.

---

## ⚙️ Installation & Exécution
1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/<utilisateur>/<repo>.git
   cd <repo>
