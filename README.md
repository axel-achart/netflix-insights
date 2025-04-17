# Netflix Insights Project (Data Analysis)

## Aspects de veille
**Intelligence Artificielle** : Branche de l'informatique, c'est la capacité des machines à effectuer des tâches typiquement associées à l'intelligence humaine, comme l'apprentissage, le raisonnement, la résolution de problème, la compréhension du langage naturel ou la prise de décision.

**Machine Learning** : Sous partie de l'IA, c'est un champ d'étude qui vise à donner aux machines la capacité d'« apprendre » à partir de données, via des modèles mathématiques.

**Pré-traitement des données** : C'est l'étape dans laquelle les données brutes sont nettoyées et structurées en vue de l'étape suivante du traitement des données.

**Analyse descriptive des données** : Méthode d'analyse qui sert à résumer de manière simple dans un tableau descriptif avec des paramètres mathématiques comme la moyenne, l'étendu etc...

## Domaine choisi : La santé
Grâce à l’intelligence artificielle, on peut :
- Détecter des maladies automatiquement sur des images médicales (ex : tumeurs, anomalies).
- Prédire l’évolution de certaines pathologies à partir de données historiques.
- Optimiser les soins en analysant les dossiers médicaux pour proposer les meilleurs traitements.
- Gérer les flux hospitaliers en prévoyant les pics d’affluence.

Exemple concret : Un hôpital peut utiliser un modèle de Machine Learning pour prédire combien de patients arriveront aux urgences chaque jour, en fonction des saisons, des événements, etc...


## Contexte et données utilisés du projet
Dans le cadre de notre formation en intelligence artificielle et data, ce projet a pour objectif de poser les bases de l’analyse de données à travers un cas concret : **l’analyse du catalogue Netflix**.

Ce projet s’inscrit dans un double objectif :

1. **Réaliser une veille autour de l’intelligence artificielle (AI Watch)** en définissant les notions clés suivantes :
   - L’intelligence artificielle,
   - Le Machine Learning (apprentissage automatique),
   - Le prétraitement des données,
   - L’analyse descriptive des données.
2. **Appliquer ces concepts à travers une analyse de données concrète**, en utilisant Python et l’environnement Jupyter Notebook.

### 🗂️ Format
- Fichier : `netflix_titles.csv`
- Nombre de lignes : ~8800 œuvres
- Nombre de colonnes : 12
- Données qualitatives & quantitatives

### 🔍 Description des colonnes

| Colonne        | Description |
|----------------|-------------|
| `show_id`      | Identifiant unique de l’œuvre |
| `type`         | Type d’œuvre : Film ou Série TV |
| `title`        | Titre de l’œuvre |
| `director`     | Réalisateur ou réalisatrice |
| `cast`         | Acteurs principaux |
| `country`      | Pays d’origine |
| `date_added`   | Date d’ajout au catalogue Netflix |
| `release_year` | Année de sortie de l’œuvre |
| `rating`       | Classification de l’œuvre (PG, TV-MA, etc.) |
| `duration`     | Durée de l’œuvre (en minutes ou en saisons) |
| `listed_in`    | Genres ou catégories |
| `description`  | Brève description du contenu |


## 📈 Observations et conclusions

Voici les observations tirés de l’analyse des données Netflix :

---

### 📊 Répartition des types d'œuvres

- La majorité du contenu est composée de **films**, sinon ce sont des **séries**.
- Cela reflète l’orientation de Netflix qui, historiquement, proposait plus de films, mais tend à équilibrer avec l'explosion des séries originales.

---

### 📅 Année de sortie

- La majorité des œuvres date des **années 2010 à 2021**.
- Peu d’œuvres datent d’avant les années 2000.
- Cela montre que Netflix se concentre principalement sur du contenu récent.

---

### 🗓️ Date d’ajout sur Netflix

- Les années **2019, 2020 et 2021** sont celles où le plus de contenus ont été ajoutés.
- On observe une accélération du catalogue, sûrement liée à la stratégie d’expansion mondiale et à la production de contenus originaux.

---

### ⏱️ Durée des œuvres

- **Films :** La majorité des films durent entre **80 et 120 minutes**.
- **Séries :** La plupart des séries comptent **1 à 3 saisons**.

---

### 🎭 Répartition des genres

- Les genres les plus fréquents sont :
  - **Dramas**
  - **Comedies**
  - **International TV Shows**
  - **Documentaries**
- Netflix mise clairement sur la diversité des goûts avec une attention particulière portée aux contenus internationaux et aux documentaires.

## 🧠 Conclusion

L’analyse du catalogue Netflix permet de :
- Mieux comprendre l’offre de contenus proposés aux utilisateurs,
- Identifier les tendances de production et de diffusion,
- Illustrer concrètement l’importance du **prétraitement**, de **l’analyse descriptive** et de **la visualisation** dans tout projet de data science.

🎯 **Ce projet constitue une première étape dans l’utilisation de l’IA appliquée à un domaine concret : le divertissement.**