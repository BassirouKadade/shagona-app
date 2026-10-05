# Shagona — téléchargement de l'application Android

Page publique de téléchargement : **https://bassiroukadade.github.io/shagona-app/**

Ce dépôt ne contient que la page (`index.html`) et les versions publiées de l'APK (onglet *Releases*). Le code de l'application est privé.

Lien direct permanent vers la dernière version :
https://github.com/BassirouKadade/shagona-app/releases/latest/download/shagona.apk

## Publier une nouvelle version

1. Construire l'APK (dépôt `shagona-mobile`) : `eas build -p android --profile apk`
2. Télécharger l'APK produit, le renommer `shagona.apk`
3. `gh release create v1.0.1 shagona.apk --repo BassirouKadade/shagona-app --title "Shagona 1.0.1" --notes "…"`

Le lien de téléchargement et la page affichent automatiquement la nouvelle version.
