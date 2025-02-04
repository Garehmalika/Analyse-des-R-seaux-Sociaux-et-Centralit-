# Analyse des Réseaux Sociaux et Centralité

## Description du Projet
Les réseaux sociaux sont devenus des éléments essentiels de notre quotidien, influençant la manière dont nous communiquons et diffusons l'information. Ce projet explore ces réseaux sous l'angle de la **théorie des graphes**, en mettant un accent particulier sur la **notion de centralité**. L'objectif est d'analyser les dynamiques internes des réseaux sociaux et d'identifier les **acteurs les plus influents** à travers différentes métriques de centralité.

## Problématique
Ce projet vise à **analyser et comparer plusieurs mesures de centralité** appliquées à différents types de réseaux sociaux. Cinq mesures de centralité sont étudiées :
- **Centralité de voisinage (Edge Centrality)**
- **Centralité de vecteurs propres (Eigenvector Centrality)**
- **Centralité de PageRank (PageRank Centrality)**
- **Centralité d’intermédiarité (Betweenness Centrality)**
- **Centralité de proximité (Closeness Centrality)**

Ces mesures permettent d'évaluer **l'importance des nœuds** dans un réseau et d'étudier **la circulation et diffusion de l'information**.

## Méthodologie
### 1. Sélection des Réseaux Analytiques
L'étude a été réalisée sur six réseaux distincts :
1. **Réseau 0** : réseau de base simplifié.
2. **Réseau d’amitié** : réseau social dans un village.
3. **Réseau universitaire** : étudiants travaillant sur des projets communs.
4. **Réseau d’entreprise** : collaborations professionnelles.
5. **Communauté de jeux en ligne** : interactions entre joueurs.
6. **Réseau international de chercheurs** : collaborations académiques.

### 2. Analyse des Mesures de Centralité
- Extraction des **graphes** représentant chaque réseau.
- Calcul des **différentes centralités** pour chaque nœud.
- Comparaison des résultats entre les réseaux pour identifier les **acteurs clés**.

### 3. Outils Utilisés
- **Python** avec les bibliothèques :
  - `networkx` pour la manipulation des graphes
  - `matplotlib` et `seaborn` pour la visualisation des résultats
  - `pandas` pour l'analyse des données

## Résultats et Conclusions
- Chaque réseau présente des dynamiques uniques influencées par sa **structure et la nature des interactions**.
- La **centralité de PageRank** est particulièrement pertinente pour identifier les **leaders d'opinion**.
- La **centralité de proximité** permet de repérer les **nœuds qui facilitent la diffusion rapide d’informations**.
- Comparer les réseaux met en évidence des **schémas communs** et des **différences structurelles** selon le contexte étudié.

## Fichiers Inclus
- `Code_Analyse_Centralite.ipynb` : Script pour le calcul des centralités et visualisation.
- `Réseaux.zip` : Ensemble des données brutes des six réseaux.
- `Rapport_Analyse_Reseaux.pdf` : Synthèse des résultats et analyse détaillée.

## Conclusion
Ce projet met en évidence l'importance des **mesures de centralité** pour l'étude des réseaux sociaux. Il constitue une base solide pour des recherches plus poussées sur la diffusion d’informations et l’identification d’acteurs influents dans différents contextes.
Pour toute question ou contribution, n’hésitez pas à contacter l’équipe projet.

