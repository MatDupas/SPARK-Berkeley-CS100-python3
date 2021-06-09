# BerkeleyX: CS100.1x


## Français:

 DESCRIPTION : 
 ------------
Ce répertoire comporte les exercices issus de la formation  "Introduction to Big Data with Apache Spark" de Berkeley.

Cette formation très appliquée permet d'aborder les transformations et les actions dans SPARK, en utilisant Pyspark.
Le cours couvre l'analyse de la qualité des données, leur exploration (EDA) et le machine learning.
Les exemples d'applications concernent le NLP ainsi qu'un moteur de recommandation pour des films.

Les notebooks ont été initiallement conçus pour Python 2 et ne fonctionnaient pas sur ma machine en Python 3.

L'avenir étant à Python 3, J'ai transformé les notebooks pour les rendres compatibles PYTHON 3, avec notamment les changements principaux suivants:
1. Fix de l'erreur lors de l'unpacking des tuples dans les fonction lambda (a ce jour, Python 3 n'acceptait pas l'unpacking à l'intérieur des fonctions lambda, pourtant très pratique. Ai du contourner le problème. 
2. Modifs des cellules utilisant Xrange (deprecié en Python 3 au profit de Range)
3. Fix des parenthèses dans les fonction print


## ENGLISH

 DESCRIPTION : 
 ------------
This folder contains all exercices from the Berkeley "Introduction to Big Data with Apache Spark" course.

This very practical course deals with transformations and actions in Spark, within the Pyspark and Python environment.
Program covers Data analysis, EDA and Machine Learning.Practicals examples include NLP in Spark and a recommending system for movies.

Notebooks were initially written in Python 2  and could not be run on my machine in Python 3.
Python 2 begining now to be a thing of the past, I decided to upgrade the code and make it compatible with PYTHON 3 with the main following Fixes:

1. Fixed tuples unpacking error inside lambda functions(at time of writing,  Python 3 doesn't accept tuple unpacking,so I had to find other ways)
2. Fixed cells using Xrange function (deprecated in python 3, as merged into the range function)
3. Fixed missing parenthesis in print statements.
