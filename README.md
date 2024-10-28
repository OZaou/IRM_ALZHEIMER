# Objectif :

Utiliser plusieurs modèles utilisants des réseaux de neuronnes convolutionnels afin de trouver le plus petit modèle possible donnant une précision d'au moins 95%

# Méthode d'entrainement :
après plusieurs tentatives de définition d'architecture mais avec un plateau autour des 85%, mais avec ces deux petit changement j'ai réussi à dépasser la barre des 90%
- La fonction d'activation MISH (référence : **https://paperswithcode.com/paper/mish-a-self-regularized-non-monotonic-neural**) 
![image](https://github.com/user-attachments/assets/de1654d5-0e36-45b8-bc78-8ce370ed7cad)

- Rajouter des couches de normalisation et Max-pooling
  
On arrive à ça :

![small](https://github.com/user-attachments/assets/95edc397-1d39-425c-8a86-20e3762bdb01)

en augmentant un peu la taille du modèle on arrive à 96% de précision :

![Mid modele](https://github.com/user-attachments/assets/943b9541-89d7-4736-89c7-1eee52e8b9ac)
