# ShodanSearch

<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/nico-vrn/ShodanSearch">
    <img src="images/logo.png" alt="Logo" width="100" height="80">
  </a>

  <h3 align="center">Shodan Search</h3>

  <p align="center">
    Recherche de nom de domaine ou IP
    <br />
   </p>
</div>

ShodanSearch est un programme en JavaScript qui utilise l'API Shodan pour effectuer des recherches sur des adresses IP et des noms de domaine. 

Il fournit des informations telles que le pays, la ville, l'organisation, les domaines et les ports.

## Comment utiliser
1. Cloner le repository.

2. Vous devez donc vous inscrire sur le site web de Shodan et obtenir une clé API  _[Documentation](https://developer.shodan.io/)_

3. Cette clé API doit être ajoutée à la variable "key" dans le fichier script.js.

4. Ouvrir le fichier index.html dans un navigateur web.

5. Entrer une adresse IP ou un nom de domaine dans la barre de recherche.

6. Cliquer sur le bouton de recherche ou appuyer sur la touche Entrée.

7. Les résultats de la recherche s'afficheront sous forme de texte.

## Fonctionnalités
Le programme offre les fonctionnalités suivantes :

* Recherche par adresse IP ou nom de domaine.
* Affichage des informations telles que le pays, la ville, l'organisation, les domaines et les ports.
* Affichage de la carte géographique de l'emplacement de l'adresse IP.
* Bouton pour ajouter les résultats de la recherche aux favoris.
* Gestion des erreurs pour les adresses IP et les noms de domaine incorrects.

## Dépendances
Le programme utilise l'API Shodan pour effectuer les recherches. 

## Contribution

Les contributions sont les bienvenues ! Pour contribuer, suivez les étapes suivantes :

1. Forkez le dépôt.
2. Créez une nouvelle branche avec un nom descriptif pour votre fonctionnalité ou correctif.
3. Faites vos modifications et soumettez-les avec un commit.
4. Créez une pull request vers la branche `main` du dépôt d'origine.

## Auteurs

- Lefranc Nicolas, [@nico-vrn](https://github.com/nico-vrn)
Crée en 2022.

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/nico-vrn/ShodanSearch?style=for-the-badge
[contributors-url]: https://github.com/nico-vrn/ShodanSearch/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/nico-vrn/ShodanSearch.svg?style=for-the-badge
[forks-url]: https://github.com/nico-vrn/ShodanSearch/network/members
[stars-shield]: https://img.shields.io/github/stars/nico-vrn/ShodanSearch.svg?style=for-the-badge
[stars-url]: https://github.com/nico-vrn/ShodanSearch/stargazers
[issues-shield]: https://img.shields.io/github/issues/nico-vrn/ShodanSearch.svg?style=for-the-badge
[issues-url]: https://github.com/nico-vrn/ShodanSearch/issues
