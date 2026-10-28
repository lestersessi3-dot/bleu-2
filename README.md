# BLE Chat : obtenir l'APK sans rien installer

1. Créez un compte gratuit sur https://github.com
2. Créez un nouveau dépôt (bouton « New »), nommé `ble-chat`.
3. Envoyez-y TOUT le contenu de ce dossier, y compris le dossier caché
   `.github` : « Add file » > « Upload files », puis glissez les fichiers.
   Si `.github` ne s'envoie pas, créez-le à la main : « Add file » >
   « Create new file », nom `.github/workflows/build.yml`, et collez le
   contenu du fichier `build.yml`.
4. Onglet « Actions » : la compilation démarre seule (3 à 6 minutes).
   Sinon : « Build APK Android » > « Run workflow ».
5. Quand la pastille est verte, ouvrez l'exécution et téléchargez
   `ble-chat-apk` en bas de page (c'est un zip contenant `app-release.apk`).
6. Envoyez l'APK sur chaque téléphone Android, ouvrez-le et autorisez
   « Installer des applications inconnues ».
7. Au premier lancement, acceptez les permissions Bluetooth.

Test : téléphone A = « Héberger », téléphone B = « Rejoindre » puis « BLEChat ».

iPhone : impossible sans Mac et compte développeur Apple (99 $/an).
