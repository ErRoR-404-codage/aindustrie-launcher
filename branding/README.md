# Branding Ain'dustrie

Sources (non versionnées) : `/root/aindustrie-launcher/branding-src/logo.png` (1254×1254, transparent)
et `fond.png` (1672×941). Pour changer le logo, remplacer ces sources puis régénérer les fichiers ci-dessous
aux mêmes tailles, et publier une nouvelle version.

| Fichier | Rôle | Généré depuis |
|---|---|---|
| `build/icon.png` | icône de l'application (1024×1024) | logo.png |
| `build/icon.ico` | icône de l'exe et de l'installeur Windows (16 → 256) | logo.png |
| `app/assets/images/SealCircle.png` | logo de l'interface (512×512) | logo.png |
| `app/assets/images/SealCircle.ico` | icône des fenêtres Windows (16 → 256) | logo.png |
| `app/assets/images/LoadingSeal.png` | logo de l'écran de chargement (512×512) | logo.png |
| `app/assets/images/LoadingText.png` | anneau qui tourne autour du logo pendant le chargement (512×512) | arc rouge (remplace le texte Helios) |
| `app/assets/images/backgrounds/0.jpg` | fond d'écran unique (1672×941) | fond.png |

Le launcher tire un fond au hasard dans `backgrounds/` : n'y laisser que `0.jpg` pour qu'il s'affiche toujours.

L'icône du serveur dans le launcher se règle côté distribution Nebula :
une image PNG dans `/root/aindustrie-launcher/root/servers/aindustrie-1.20.1/`, puis régénérer la distribution.
