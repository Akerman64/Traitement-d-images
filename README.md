Projet de Classification d'Images de Visages Célébrités avec CNN et Transfert Learning

Objectif du projet :
Ce projet vise à développer un modèle de classification d'images pour identifier des célébrités à partir de leurs visages. Le dataset utilisé contient des photos de 17 acteurs et actrices américains, avec 100 images par catégorie. L'objectif est d'analyser ce dataset, de créer un modèle de classification d'images utilisant un CNN (réseau de neurones convolutifs) construit "from scratch", puis de tester l'approche d'apprentissage par transfert en utilisant MobileNetV2 pour améliorer les performances.

Détails du Dataset :
Nombre de classes : 17 (acteurs/actrices célèbres)
Nombre d'images : 100 images par classe
Source : Kaggle - Celebrity Face Image Dataset
Taille des images : Les images sont de dimensions variées, nécessitant un redimensionnement avant l'entraînement.
Méthodologie :
Téléchargement et analyse du dataset :

Téléchargement du dataset et analyse de la répartition des images, des dimensions et de la qualité des photos.
Prétraitement des données : redimensionnement des images et normalisation des pixels.
Création d'un modèle CNN "from scratch" :

Conception et entraînement d'un modèle CNN à partir de zéro.
Séparation du dataset en ensembles d’entraînement, de validation et de test.
Evaluation des performances du modèle et analyse des résultats.
Apprentissage par Transfert Learning avec MobileNetV2 :

Utilisation du modèle MobileNetV2 pré-entraîné sur ImageNet.
Geler les couches convolutives de base et ajouter une tête de classification personnalisée.
Réévaluation des performances avec cette approche.
Amélioration des performances :

Application de techniques d'augmentation de données pour améliorer la généralisation du modèle.
Fine-tuning des couches supérieures de MobileNetV2 pour affiner le modèle.
Test du modèle avec de nouvelles images téléchargées sur Internet pour évaluer sa robustesse.
Résultats attendus :
Comparaison des performances du modèle CNN "from scratch" et de l'approche par transfert learning.
Tests de généralisation avec de nouvelles photos et ajustements pour améliorer la précision.
Analyse des stratégies d'amélioration : augmentation des données, régularisation, et collecte de données supplémentaires.
Technologies utilisées :
Langage : Python
Bibliothèques : TensorFlow, Keras, NumPy, Matplotlib, PIL (Pillow)
Plateforme : Kaggle pour le dataset, Jupyter Notebook pour le développement
Améliorations futures possibles :
Utilisation d'autres modèles de transfert learning comme VGG16 ou ResNet.
Amélioration de l'interface utilisateur pour intégrer le modèle dans une application en ligne.
Expérimentation avec d'autres techniques de prétraitement des images, comme la réduction de bruit et le redressement des visages.
