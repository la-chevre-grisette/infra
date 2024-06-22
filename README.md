<p align="center"><a href="https://lachevregrisette.fr" target="_blank"><img src="https://raw.githubusercontent.com/la-chevre-grisette/art/main/images/logo.svg" width="300" alt="Le logo La chèvre Grisette"></a></p>

<p align="center">
<a href="https://creativecommons.org/licenses/by-sa/4.0/deed.fr"><img src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" alt="Licence"></a>
</p>

## Pré-requis

* Un nom de domaine chez OVH.
* Une base de donnée MySQL >= 5.7 chez OVH (qui fait partie de l'offre d'hébergement) avec `utf8mb4_general_ci` comme encodage (**attention ce n'est pas le cas par défaut !**).
* Activer l'accès SFTP.

## Préparation

Ce projet nécessite les logiciels suivants:

* [`rclone`](https://rclone.org/)
* [`rye`](https://rye.astral.sh/)

Une fois tous ces éléments installés et configurés, installer les dépendances:

```sh
rye sync
```

## Déploiement

Lancer le déploiement ou la mise à jour de l'infrastructure:

```sh
rye run deploy
```

## Licences

* La licence de ce projet est décrite dans [LICENCE.md](LICENSE.md).
* Certains éléments comme le logo et autres éléments artistiques utilisent [une autre licence](https://github.com/la-chevre-grisette/art/blob/main/LICENCE.md).
