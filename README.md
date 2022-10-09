# Projet-2-Analysez-des-donnees-de-systemes-educatifs
ROJET 2- ANALYSEZ DES DONNEES DE SYSTEMES
EDUCATIFS

1-PROBLEMATIQUE
		La start-up de la EdTech, nommée academy, propose des contenus de formation en
		ligne pour un public de niveau lycée et université.
		Dans le cadre d’un projet d’expansion à l’international de l’entreprise,
		une première mission d’analyse exploratoire est initiée, afin de déterminer si les
		données sur l’éducation de la banque mondiale permettent d’informer le projet
		d’expansion.
		Ci-dessous les différentes questions à explorer :
			 Quels sont les pays avec un fort potentiel de clients pour nos services ?
			 Pour chacun de ces pays, quelle sera l’évolution de ce potentiel de
			     clients ?
			 Dans quels pays l'entreprise doit-elle opérer en priorité ?

2-PRESENTATION DU JEU DU JEU DONNEES
		1-Sources:
			https://datacatalog.worldbank.org/dataset/education-statistics
			http://datatopics.worldbank.org/education/

		2-Fichiers: .

		EdStatsData: 
		fichier de base ; nous renseigne sur les codes pays, les codes series, les relevés des taux de 		1970 à 2100.

		nombfre de lignes: 886 930
		nombre de colonnes: 70
		nombre de données dupliquées: 0

		EdStatsCountry:
		Contient des informations sur les pays, les regions et leur niveau de revenu.

		nombfre de lignes: 241
		nombre de colonnes: 32
		nombre de données dupliquées:0

		EdStatsCountry-Series:
		contient des informations sur les code pays , les codes series et leur description.

		nombfre de lignes: 613
		nombre de colonnes: 4
		nombre de données dupliquées: 0

		EdStatsFootNote:
		Contient des informations sur les pays, les series code ainsi la description des années de 			collecte de données.

		nombfre de lignes: 643638
		nombre de colonnes: 5
		nombre de données dupliquées:0

		EdStatsSerie:
		Fournit des informations sur les codes series ainsi que la
		composition des populations.

		nombfre de lignes: 3665
		nombre de colonnes: 21
		nombre de données dupliquées: 0

 3-COMPETENCES EVALUEES

		-Mettre en place un environnement Python
		-Effectuer une représentation graphique à l'aide d'une librairie Python adaptée
		-Manipuler des données avec des librairies Python spécialisées
		-Maîtriser les opérations fondamentales du langage Python pour la Data Science
		-Utiliser un notebook Jupyter pour faciliter la rédaction du code et la collaboration



_______________________________________________________________________________


PROJET 4 Anticipez les besoins en consommation de bâtiments
1-PROBLEMATIQUE
		La ville de Seattle veut atteindre son objectif de ville neutre en émissions de carbone en 			2050.
		Une étude est initiée et porte sur les émissions des bâtiments non destinés à l’habitation.
		Des relevés minutieux ont été effectués en 2015 et en 2016. Cependant, ces relevés sont 			coûteux à obtenir, et à partir de ceux déjà réalisés, on va tenter de prédire les émissions de 		CO2 et la consommation totale d’énergie de bâtiments pour lesquels elles n’ont pas 			encore été mesurées.
		* Il va falloir aussi évaluer l’intérêt de l’ENERGY STAR Score en modélisant avec et 			   sans.
		* Nous allons donc entraîner plusieurs algorithmes de régression linéaires.
		A l’issue de l’ apprentissage, retenir le ou les modèles de regression à performance élevée.     		Ensuite procéder à l’optimisation des paramètres en utilisant la méthode du Gridsearch.

2-COMPETENCES EVALUEES

		-Mettre en place le modèle d'apprentissage supervisé adapté au problème métier
		-Adapter les hyperparamètres d'un algorithme d'apprentissage supervisé azn de
		  l'améliorer
		-Transformer les variables pertinentes d'un modèle d'apprentissage supervisé
		-Évaluer les performances d’un modèle d'apprentissage supervisé

