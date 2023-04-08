# lorenz
Ce code permet de calculer l'indice de Gini à partir d'un ensemble de données de dépenses.

Tout d'abord, la première ligne récupère les valeurs négatives des données de la variable "montant" à partir du DataFrame "data" et les stocke dans la variable "depense". Ensuite, la variable "dep" contient la valeur absolue des dépenses négatives, ce qui permet d'obtenir une liste de valeurs positives.

La variable "n" correspond à la taille de la liste "dep".

## Ensuite, le code calcule la fréquence cumulée croissante de la liste "dep" et stocke les résultats dans la variable "lorenz". La variable "absis" est ## créée pour représenter les valeurs de l'axe horizontal pour la courbe de Lorenz.

La courbe de Lorenz est tracée à l'aide de la fonction "plt.plot(absis, lorenz)" qui permet de représenter graphiquement la distribution des dépenses en fonction de leur fréquence cumulée.

La première bissectrice est également tracée à l'aide de la fonction "plt.plot([0,1],[0,1])". Cette droite représente l'égalité parfaite entre les revenus et les dépenses.

#Pour exécuter ce code sur Google Colab, suivez les étapes suivantes :

    Ouvrez votre navigateur Web et accédez à Google Colab (https://colab.research.google.com/).
    Connectez-vous à votre compte Google si ce n'est déjà fait.
   ### Cliquez sur le bouton "Nouvelle note" pour ouvrir un nouveau notebook.
    Dans la première cellule du notebook, vous pouvez importer les bibliothèques nécessaires en utilisant les commandes suivantes :
