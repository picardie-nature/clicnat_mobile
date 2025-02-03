# Clicnat-mobile

Version de l'appli [Occtax-mobile](https://github.com/PnX-SI/gn_mobile_occtax) customisée pour PicNat.

## Customisations

* ID d'application spécifique, permettant l'installation aux côtés d'autes applis Occtax (v. `occtax/build.gradle`)
* nom d'appli 'Clicnat mobile' (v. `occtax/src/main/res/values/strings.xml`)
* couleurs Clicnat (v. `occtax/src/main/res/values/colors.xml`) 
* logo Clicnat (v. fichiers `occtax/src/main/res/mipmap*`)

## Configuration de l'application

Le fichier de configuration de l'application doit être mis sur le serveur, dans le même repo que l'apk de l'application.

Pous suivre ses modificaions, ce fichier est pushé avec le code : `app_settings.json`. En cas de modification, les pusher ici avant de copier la nouvelle version du fichier sur le serveur.