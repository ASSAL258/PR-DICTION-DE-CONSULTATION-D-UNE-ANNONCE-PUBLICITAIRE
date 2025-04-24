Prédiction du clic sur une publicité en ligne avec Python
Ce projet a pour objectif de prédire si un internaute cliquera ou non sur une publicité en ligne, en se basant sur son profil et son comportement de navigation. Plusieurs algorithmes d’apprentissage supervisé ont été utilisés pour construire et comparer les modèles, notamment la Régression Logistique, LDA, QDA et la Forêt Aléatoire (Random Forest).

Jeu de données
Le jeu de données utilisé dans ce projet contient les variables suivantes :

Daily_Time_Spent_on_Site : Temps passé sur le site par l'utilisateur (en minutes)

Age : Âge de l'utilisateur

Area_Income : Revenu moyen de la zone géographique de l'utilisateur

Daily_Internet_Usage : Utilisation moyenne d'Internet par jour (en minutes)

Ad_Topic_Line : Sujet de la publicité affichée

City et Country : Localisation géographique de l'utilisateur

Timestamp : Date et heure de l’interaction

Clicked_on_Ad : Variable cible (1 si l'utilisateur a cliqué sur la publicité, 0 sinon)

Objectif
L’objectif est de :

Réaliser une analyse exploratoire des données (EDA)

Prétraiter et encoder les variables catégorielles

Entraîner et évaluer plusieurs modèles de classification

Sélectionner le meilleur modèle selon l'accuracy et le F1-score

Utiliser le modèle retenu pour prédire le comportement de nouveaux internautes
