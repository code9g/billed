# Billed

Projet 9 de la formation "Développeur JavaScript / React" de OpenClassRoom

## NVM

Pour que ce projet puisse fonctionner, il faut pouvoir utiliser la version 18.16.1 de node.js.

Installez NVM si ce n'est pas encore fait

```
nvm install 18.16.1
nvm use 18.16.1
```

N'hésitez pas à vérifier la version en cours d'utilisation avec :

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

Dans le terminal:

```
cd back
npm install
npm run run:dev
```

## Lancement de la partie front

Dans un nouveau terminal:

```
cd front
npm install
```

Si vous n'utilisez pas l'extension Live Server:

```
npm install -g live-server
live-server
```

sinon, Faites juste un "Go Live"

### administrateur :

```
utilisateur : admin@company.tld
mot de passe : admin
```

### employé :

```
utilisateur : employee@company.tld
mot de passe : employee
```
