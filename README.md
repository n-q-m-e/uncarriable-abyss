# uncarriable-abyss

Site vitrine conceptuel, purement visuel. Zéro texte, zéro UI, zéro interaction — une expérience immersive d'océan 3D temps réel.

## Stack

- HTML / CSS / JavaScript vanilla
- Three.js (CDN)
- GLSL custom shaders (vertex + fragment)
- Post-processing : film grain, vignette

## Features

- Océan Gerstner waves (4 couches, vitesse physique)
- Fresnel sky reflections
- Subsurface scattering sur les crêtes
- Mousse organique procédurale (3 couches de noise)
- Ciel dynamique avec soleil qui monte
- Brume atmosphérique à l'horizon
- Caméra drift subtile
- Film grain + vignette post-process

## Installation

Aucune dépendance. Ouvrir `index.html` dans un navigateur ou déployer sur GitHub Pages.

```
git clone https://github.com/n-q-m-e/uncarriable-abyss.git
cd uncarriable-abyss
# ouvrir index.html ou servir avec n'importe quel serveur statique
npx serve .
```

## Déploiement

Compatible GitHub Pages — fichier `index.html` à la racine, zéro build.
