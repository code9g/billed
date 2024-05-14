# Billed

Projet 9 de la formation "Développeur JavaScript / React" de OpenClassRoom

## Utilisez une version de node compatible

Si vous utilisez une version récente de node sur votre ordinateur, il se peut qu'il y ai des erreurs lors de l'installation de certaines dépendances. Pour cela il est important de vous assurer que vous ayez une version de node compatible par exemple node v16 ou v18.

Voici quelques indications pour gérer les version de node sur votre ordinateur par le biais de Node Version Manager:

### Sur Windows

- Installer NVM pour Windows (https://github.com/coreybutler/nvm-windows/tags)
- Ouvrir Powershell en mode administrateur
- Entrer la commande `Set-ExecutionPolicy RemoteSigned` pour pouvoir gérer l’execution de scripts dans powershell
- Fermer toutes les instances de terminal
- Entrer la commande `npm install -g win-node-env` pour installer la gestion des variables d’environnement node pour window

### Sur Mac

- Installer NVM pour Mac (https://github.com/nvm-sh/nvm)

### Changer de version de Node.js

Pour changer de version de node.js, il vous suffit d'installer la version si cela n'a pas été fait :

```
nvm install 18.16.1
```

Puis d'effectuer le changement avec :

```
nvm use 18.16.1
```

Et si vous voulez vérifier la version en cours :

```
nvm current
```

ou

```
node --version
```

et pour revenir à la dernière version :

```
nvm use latest
```

## Mise en place de la partie back

Installez les dépendances :

```
cd back
npm install
```

Puis lancez le serveur :

```
npm run run:dev
```

## Mise en place de la partie front

Dans un nouveau terminal:

```
cd front
npm install
```

Si vous n'utilisez pas l'extension Live Server, vous pouvez installer live-server :

```
npm install -g live-server
```

et le lancer :

```
live-server
```

Sinon, Faites juste un "Go Live" (depuis la barre d'état) ou "Open with Live Server" (click droit) !

## Accès

### Administrateur

```
Utilisateur : admin@company.tld
Mot de passe : admin
```

### Employé

```
Utilisateur : employee@company.tld
Mot de passe : employee
```
