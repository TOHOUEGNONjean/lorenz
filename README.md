# LA COURBE DE Lorenz
Ce code permet de calculer l'indice de Gini à partir d'un ensemble de données de dépenses.

La courbe de Lorenz est une représentation graphique qui permet de visualiser la répartition de la richesse ou des dépenses d'une population. Elle a été introduite par le mathématicien américain Max O. Lorenz en 1905.

La courbe de Lorenz est construite en traçant la fréquence cumulée croissante des valeurs d'une variable (par exemple, les revenus ou les dépenses) sur l'axe des ordonnées et la fréquence cumulée croissante de la population correspondante sur l'axe des abscisses. L'aire entre la courbe de Lorenz et la première bissectrice (qui représente l'égalité parfaite) mesure l'inégalité de la répartition de la richesse ou des dépenses dans la population. Plus cette aire est grande, plus l'inégalité est grande.

# lINDICE DE Gini
Corrado Gini était un statisticien et mathématicien italien, né le 23 mai 1884 à Motta di Livenza et décédé le 13 mars 1965 à Rome. Il est principalement connu pour son travail sur la théorie des statistiques et de la corrélation, ainsi que pour l'invention de l'indice de Gini en 1912.

L'indice de Gini est un outil statistique utilisé pour mesurer l'inégalité de la distribution des richesses ou des revenus dans une population donnée. L'indice de Gini est un nombre compris entre 0 et 1, où 0 correspond à une distribution parfaitement égalitaire des richesses ou des revenus, tandis que 1 correspond à une concentration maximale des richesses ou des revenus entre un nombre réduit de personnes.

L'indice de Gini est largement utilisé dans les études économiques et sociales pour évaluer la répartition des richesses ou des revenus dans une population donnée, et pour évaluer l'efficacité des politiques publiques visant à réduire les inégalités.

Tout d'abord, la première ligne récupère les valeurs négatives des données de la variable "montant" à partir du DataFrame "data" et les stocke dans la variable "depense". Ensuite, la variable "dep" contient la valeur absolue des dépenses négatives, ce qui permet d'obtenir une liste de valeurs positives.

La variable "n" correspond à la taille de la liste "dep".

Ensuite, le code calcule la fréquence cumulée croissante de la liste "dep" et stocke les résultats dans la variable "lorenz". La variable "absis" est ## créée pour représenter les valeurs de l'axe horizontal pour la courbe de Lorenz.

La courbe de Lorenz est tracée à l'aide de la fonction "plt.plot(absis, lorenz)" qui permet de représenter graphiquement la distribution des dépenses en fonction de leur fréquence cumulée.

La première bissectrice est également tracée à l'aide de la fonction "plt.plot([0,1],[0,1])". Cette droite représente l'égalité parfaite entre les revenus et les dépenses.

#Pour exécuter ce code sur Google Colab, suivez les étapes suivantes :

 Ouvrez votre navigateur Web et accédez à Google Colab (https://colab.research.google.com/).
 Connectez-vous à votre compte Google si ce n'est déjà fait.
Cliquez sur le bouton "Nouvelle note" pour ouvrir un nouveau notebook.
Dans la première cellule du notebook, vous pouvez importer les bibliothèques nécessaires en utilisant les commandes suivantes :

## TOHOUEGNON Jean-Baptiste
