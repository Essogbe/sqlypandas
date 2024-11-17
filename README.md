
# SQLyPandas
![ ](sqlypdandas.png)
**SQLyPandas** est un projet éducatif créé dans le but d'aider les utilisateurs à apprendre et à s'exercer à manipuler des bases de données SQL en utilisant des fonctions inspirées de la bibliothèque Pandas. Ce projet permet aux utilisateurs de découvrir et de comprendre comment effectuer des opérations SQL courantes, tout en s'appuyant sur des concepts familiers de Pandas.

---

## Objectif du projet

L'objectif de **SQLyPandas** est d’offrir un moyen simple et pratique pour les utilisateurs d'apprendre à interagir avec une base de données SQL à travers des fonctions similaires à celles de Pandas. En utilisant ces fonctions, les utilisateurs peuvent effectuer des tâches courantes de manipulation de données (sélection, jointure, gestion des valeurs manquantes, calcul de statistiques, etc.) de manière fluide et compréhensible.

Ce projet n'est pas destiné à être une alternative complète à Pandas ou à SQL, mais plutôt à être un outil d'apprentissage pour ceux qui souhaitent se familiariser avec les bases de données SQL tout en utilisant des méthodes simples et compréhensibles.

Les principales fonctionnalités incluent :

- Sélection des colonnes avec `get_columns()`
- Manipulation de valeurs manquantes avec `dropna()`
- Fonctionnalités de `group_by()`, `join()` et `unique()`
- Calcul de statistiques descriptives (`describe()`)
- Et bien plus...

---

## Fonctionnalités principales

### 1. **Sélection de colonnes :**
   La fonction `get_columns()` permet de récupérer des colonnes spécifiques dans une table SQL, avec une syntaxe proche de Pandas.

### 2. **Manipulation des valeurs manquantes :**
   `dropna()` est utilisée pour éliminer les lignes contenant des valeurs manquantes dans les colonnes spécifiées, suivant un comportement similaire à `dropna()` de Pandas.

### 3. **Exploration des données :**
   Des fonctions comme `shape_sql()`, `head_sql()`, et `tail_sql()` offrent des moyens pratiques d'explorer les données de votre table, avec une syntaxe proche de Pandas.

### 4. **Statistiques descriptives :**
   La fonction `describe()` retourne les statistiques de base pour une colonne donnée, notamment le compte, la moyenne, les quantiles, etc.

### 5. **Calcul de quantiles et écart-type :**
   `quantile()` et `get_std()` permettent de calculer des quantiles spécifiques ainsi que l'écart-type des données d'une colonne.

### 6. **Opérations de jointure et de regroupement :**
   La fonction `join()` permet de réaliser des jointures SQL, et `group_by()` facilite l'agrégation des données par groupe, en incluant une limite pour la taille des résultats.

---

## TO-DO

### Fonctions supplémentaires à implémenter :
1. **Mise à jour des enregistrements (`update()`) :** Une fonction pour mettre à jour des valeurs spécifiques dans une table SQL.
2. **Suppression d'enregistrements (`delete()`) :** Implémentation d'une fonction permettant de supprimer des enregistrements basés sur une condition donnée.
3. **Tri des données (`sort()`) :** Une fonction pour trier les données d'une table selon des colonnes spécifiques, avec des options de tri ascendant ou descendant.
4. **Fusion de tables (`merge()`) :** Une fonction permettant de fusionner plusieurs tables en utilisant des clés similaires, comme `merge()` dans Pandas.
5. **Vérification de doublons (`drop_duplicates()`) :** Ajouter une fonction pour éliminer les doublons d'une table SQL.

### Autres améliorations :
- Ajouter un support pour les **jointures complexes** (par exemple, avec des conditions multiples).
- Implémenter des **fonctionnalités avancées d'agrégation** (comme `sum()`, `mean()`, etc.) dans la fonction `group_by()`.
- Ajouter des **tests unitaires** pour garantir la stabilité du code.

---

## Contributions

Si vous souhaitez contribuer au projet, n'hésitez pas à soumettre une pull request avec vos améliorations ou suggestions. Nous acceptons également les rapports de bugs ou toute autre forme d'amélioration pour rendre SQLyPandas encore plus utile.

---

## Licence

Ce projet est sous licence **MIT**. Vous êtes libre de l'utiliser et de le modifier selon vos besoins, tant que vous incluez une copie de cette licence dans toute version du code que vous distribuez.

---

Merci de contribuer à SQLyPandas et bon apprentissage de SQL !

---

Ce format met bien l'accent sur l'aspect pédagogique du projet, en précisant que l'objectif est d'offrir un moyen facile et compréhensible d'apprendre SQL avec des fonctions inspirées de Pandas.