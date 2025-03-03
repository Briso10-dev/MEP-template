# @Briso/MEP-starter

## Vue d'ensemble

`@Briso/MEP-starter` est un projet de démarrage TypeScript conçu pour simplifier le développement d'applications Express.js. Ce kit de démarrage inclut les configurations et dépendances essentielles pour vous permettre de démarrer rapidement, tout en appliquant des normes de qualité et de cohérence du code avec ESLint et Prettier.

## Fonctionnalités

- TypeScript pour le typage statique et une intelligence de code avancée
- Express.js pour la création d'APIs et d'applications web robustes
- ESLint et Prettier pour la qualité et le formatage du code
- Support des variables d'environnement avec dotenv et env-var
- Middleware de compression pour améliorer les performances
- Middleware de limitation de débit pour protéger votre application
- Intégration de Swagger pour la documentation des APIs

## Prérequis

- Node.js >= 20.12.0
- Yarn >= 1.22.19

> Note : Utiliser Yarn pour ce projet.

## Pour commencer

### Installation

Clonez le dépôt et installez les dépendances :

```bash
git clone https://github.com/worketyamo/ts-starter.git
cd ts-starter
yarn install
```

### Exécution en mode développement

Pour démarrer le serveur de développement avec redémarrages automatiques en cas de modifications des fichiers, utilisez :

```bash
yarn dev
```

### Compilation du projet

Pour compiler le projet pour la production, utilisez :

```bash
yarn build
```

### Démarrage de l'application

Pour démarrer l'application après la compilation, utilisez :

```bash
yarn start
```

## Scripts

- **dev** : Lance le serveur de développement avec ts-node-dev
- **build** : Nettoie le dossier dist et compile le code TypeScript
- **start** : Exécute le code JavaScript compilé à partir du dossier dist

## Utilisation

Démarrage du serveur
Pour démarrer le serveur, exécutez la commande suivante :

```bash
yarn start
```
Le serveur sera lancé sur le port : http://localhost:3000

Documentation de l'API
La documentation de l'API est accessible à l'adresse suivante :

```sh
http://localhost:3000/api-docs
 ```
## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Contribution

Les contributions sont les bienvenues ! Veuillez ouvrir un problème ou soumettre une demande de tirage.

## Informations supplémentaires

Pour toute question ou support supplémentaire, veuillez contacter les mainteneurs du projet.
