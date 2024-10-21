-Introduction :

Le modèle Lasso "Least Absolute Shrinkage and Selection Operator" est une méthode statistique puissante en machine learning. Elle a été introduite pour la première fois en 1996 par le professeur de statistiques Robert Tibshirani. LASSO introduit des paramètres dans la somme d'un modèle, en lui donnant une contrainte qui va garder cette somme dans une plage autorisée.
Selon une étude de Kaggle, Lasso est parmi les techniques de régression les plus utilisées maintenant et plus de 30 % des participants aux compétitions en IA l'adopte dans leurs modèles. 
Cette popularité s'explique par sa capacité à fournir des solutions précises pour des données de grande dimension. 

-Principe :
1-Régression linéaire
C’est une extension de la régression linéaire classique. Dans la régression linéaire, on veut modéliser la relation entre une variable dépendante (ou cible) et un ensemble de variables indépendantes (ses caractéristiques) par une combinaison linéaire. Le modèle cherche à trouver les coefficients Béta qui minimisent l'erreur entre les valeurs prédites et les valeurs réelles de la variable dépendante.
2-Régularisation L1 
La régularisation L1 consiste à introduire une pénalité alpha  dans la fonction de coût du modèle pour décourager les coefficients de prendre des valeurs trop élevées. Cela aide à prévenir le surajustement donc le modèle s'adapte trop étroitement aux données d'entraînement.
 y = β₀ + β₁x₁ + β₂x₂ + ... + βₚxₚ + ε Où :
y est la variable dépendante (cible).
β₀, β₁, β₂, ..., βₚ sont les coefficients (paramètres) à estimer.
x₁, x₂, ..., xₚ sont les variables indépendantes (caractéristiques).
ε représente le terme d’erreur.

-Problématique :

Notre objectif principal est d'automatiser ce processus pour diriger chaque catégorie d'aluminium vers son industrie spécifique.
Pour ce faire, nous prévoyons d'intégrer des capteurs LIBS (Spectroscopie par Désintégration Laser Induite). Ces capteurs produiront des spectres à partir des échantillons, sur lesquels nous baserons la création d'un modèle d'apprentissage automatique permettant d'identifier chaque catégorie d'aluminium analysée par le capteur. Le modèle central de cette étude est le modèle LASSO.

Dans ce contexte, comment pouvons-nous construire un modèle LASSO en déterminant le coefficient de pénalisation alpha optimal ?

 
