# Branding Ain'dustrie — emplacement du logo

Le logo n'est pas encore fourni : les images Helios d'origine restent en place.
Pour appliquer le logo, remplacer ces fichiers (mêmes noms, mêmes formats) puis publier une nouvelle version :

| Fichier | Rôle | Format |
|---|---|---|
| `build/icon.png` | icône de l'application et de l'installeur Windows | PNG 512×512 (min. 256×256), fond transparent |
| `app/assets/images/SealCircle.png` | logo rond de l'interface | PNG 256×256 |
| `app/assets/images/SealCircle.ico` | icône de fenêtre Windows | ICO multi-tailles (16–256) |
| `app/assets/images/LoadingSeal.png` | logo de l'écran de chargement | PNG 256×256 |
| `app/assets/images/LoadingText.png` | texte sous le logo de chargement | PNG transparent |
| `app/assets/images/backgrounds/*.jpg` | fonds d'écran (optionnel) | JPG 1920×1080 |

L'icône du serveur dans le launcher se règle côté distribution Nebula :
une image PNG dans `/root/aindustrie-launcher/root/servers/aindustrie-1.20.1/`, puis régénérer la distribution.
