# StickerSmash

<img src="assets/adaptive-icon.png" width="100" alt="StickerSmash Logo" />

## À propos du projet

StickerSmash est une application mobile React Native qui permet aux utilisateurs de créer des compositions d'images amusantes en ajoutant des autocollants à leurs photos. Ce projet a été développé en suivant le [tutoriel officiel d'Expo](https://docs.expo.dev/tutorial/introduction/).

⚠️ **Note:** Je ne suis pas l'auteur original de cette application. Ce projet est une implémentation du tutoriel StickerSmash fourni par Expo.

## Fonctionnalités

- Sélection d'images depuis la galerie de l'appareil
- Ajout d'autocollants prédéfinis aux images
- Positionnement et redimensionnement des autocollants
- Enregistrement des créations dans la galerie

## Captures d'écran

<!-- Si vous avez des captures d'écran, ajoutez-les ici -->

## Prérequis

- Node.js (version 14 ou supérieure)
- npm ou yarn
- Expo CLI
- [Expo Go](https://expo.dev/client) sur votre appareil mobile (pour le développement)

## Installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/NOMO-Gabriel/StickerSmash.git
   cd StickerSmash
   ```

2. Installez les dépendances :
   ```bash
   npm install
   # ou
   yarn install
   ```

## Lancement du projet

### Mode développement

Pour lancer l'application en mode développement :

```bash
npx expo start
```

Scannez le code QR avec l'application Expo Go sur votre appareil mobile.

### Création d'un APK (Android)

Pour générer un fichier APK :

```bash
eas build -p android --profile preview
```

Cette commande va générer un APK dans le cloud d'Expo et vous fournira un lien pour le télécharger une fois prêt.

## Structure du projet

```
StickerSmash/
├── assets/             # Images, icônes et ressources
├── components/         # Composants React
├── App.js              # Point d'entrée de l'application
├── app.json           # Configuration Expo
├── package.json       # Dépendances
└── README.md          # Ce fichier
```

## Technologies utilisées

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Expo Image Picker](https://docs.expo.dev/versions/latest/sdk/imagepicker/)
- [Expo Media Library](https://docs.expo.dev/versions/latest/sdk/media-library/)
- [React Native Gesture Handler](https://docs.swmansion.com/react-native-gesture-handler/)
- [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/)

## Crédits

- Tutoriel original : [Create your first Expo app (StickerSmash)](https://docs.expo.dev/tutorial/introduction/)
- Développé par : [NOMO-Gabriel](https://github.com/NOMO-Gabriel)

## Licence

Ce projet est distribué sous la licence MIT. Voir le fichier `LICENSE` pour plus d'informations.