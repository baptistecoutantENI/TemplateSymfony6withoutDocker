# Template Symfony 6 sans Docker

Ce projet est un modèle de base pour démarrer un projet Symfony 6 sans l'utilisation de Docker. Il inclut la configuration de Symfony, la gestion des dépendances avec Composer, et la compilation des assets avec NPM.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- PHP 8.1 ou supérieur
- Composer
- Node.js et npm
- Symfony CLI (optionnel mais recommandé)

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/baptistecoutantENI/TemplateSymfony6withoutDocker.git
   cd TemplateSymfony6withoutDocker

2. Installez les dépendances PHP avec Composer :
   ```bash
   composer install

3. Installez les dépendances JavaScript avec npm :
   ```bash
   npm install

4. Lancez le script de compilation et de surveillance des assets :
   ```bash
   npm run watch

    Note : Laissez cette commande tourner en arrière-plan dans un terminal (par exemple, dans PhpStorm).

5. Démarrez le serveur Symfony :
   ```bash
   symfony server:start
   OU
   php bin/console server:start 127.0.0.1:8000

    Note : Laissez également cette commande tourner en arrière-plan dans un terminal (par exemple, dans PhpStorm).


## Configuration de la base de données
  Vous devez configurer vos informations de connexion à la base de données dans le fichier .env. Mettez à jour les variables suivantes avec vos informations :
  Assurez-vous que votre base de données est configurée et que les informations de connexion sont correctes.

## Accéder à l'application
  Une fois le serveur démarré, vous pouvez accéder à l'application à l'adresse suivante :

    http://127.0.0.1:8000

## Profitez de Symfony Turbo
  Symfony Turbo est déjà intégré dans ce projet pour améliorer les performances et l'expérience utilisateur. Profitez des fonctionnalités avancées et des optimisations offertes par Symfony Turbo dès maintenant !



