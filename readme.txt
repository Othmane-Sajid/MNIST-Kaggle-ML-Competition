Pour l'utilisation de Logistic_reg.py, il suffit d'indiquer en début de code 
les path respectifs des fichiers train_inputs, train_labels et test_inputs.

Le code est très intuitif est suffisamment commenté. 

La classe LogisticRegression contient toutes les méthodes pour l'entrainement et la prédiction. 
L'utilisateur peut s'il le souhaite préciser certains hyperparamètres pour l'optimisation (la descente de gradient).
Ces paramètres sont : 
-learnRate
-numIteratitions
-mu (pour la régularisation L2).

Ces paramètres auront évidemment un impact sur le temps requis pour l'entrainement ainsi que la qualité des prédictions. 

La spécification de ces hyperparamètres se fait via une méthode de classe:
LogisticRegression .update_optimization_parameters (learnRate = 0.2, numIterations=300, mu=0.01).


Également, nous invitons fortement les correcteurs à regarder plutôt les pages Google collab pour une expérience plus dynamique : 

Analyse préliminaire et régression logistique : 
https://colab.research.google.com/drive/19PQNHsCtU_bMeHrdPgOgPAUQN3sehldD?usp=sharing 


Tous les autres modèles (SVM, Naive Bayes, Knn, Neural Network) : 
https://colab.research.google.com/drive/17v-XDT_FbhuqLrY1HR78mnpwgrC4NoSE?usp=sharing 


