# CapsNet pour la Classification des Images Satellitaires - EuroSAT (RGB 64x64)

## 🚀 **Description du Projet**
Ce projet implémente un **réseau de capsules (CapsNet)** pour classifier les images satellites du jeu de données **EuroSAT**. L'objectif principal est de démontrer l'efficacité des CapsNets pour capturer les relations spatiales complexes et améliorer la robustesse face aux transformations telles que la rotation et le bruit.

Le jeu de données **EuroSAT** comprend des images RGB (64x64) représentant différentes catégories terrestres, telles que :
- Zones agricoles
- Forêts
- Zones résidentielles
- Routes, etc.

---

## 🛠️ **Fonctionnalités**
- Prétraitement des images satellites avec augmentation des données.
- Architecture avancée basée sur un réseau de capsules :
  - **Couche de convolution** pour l'extraction des caractéristiques.
  - **Capsules primaires** pour encoder les entités locales.
  - **Capsules supérieures** pour les prédictions de classe.
- Fonction de perte marginale avec reconstruction supervisée.
- Visualisation des résultats :
  - Activations des capsules.
  - Reconstructions des images.

---

