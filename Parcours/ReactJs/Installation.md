# React

## Table des matières

1. [installation](./Installation.md) ←
2. [Introduction](./introduction.md) 
3. [Dom](./Dom.md)
4. [Props et State](./PropsEtState.md)
5. [Interaction entre component P1](./InteractionEntreComponentPartie1.md) 
6. [Interaction entre component P2](./InteractionEntreComponentPartie2.md) 
7. [Binding](./Binding.md)


## Installation
Pour travailler en react, nous allons avoir besoin d'un environnement de travail principalement basé sur Node js. S'il n'est pas déjà installé, go on the terminal

```sudo
sudo apt-get update
sudo apt-get install nodejs npm
```

## Create React App
On va maintenant créer un dossier de travail pour React dans lequel on mettra tous les projets.
Ensuite nous allons installer et créer notre projet react avec le terminal.

Enfin nous utiliserons npm afin d'installer create-react-app en global. Cette commande est là pour créer le squelette de notre application mais on pourrait très bien le faire à la main.

```create-react-app
npm install -g create-react-app
```

Une fois l'installation terminée, on peux créer le dossier ou l'on souhaite stocker l'application, grace à la commande "create" suivie du nom de notre application: 

```create-react-app
create-react-app serie
```
- [Plus d'info](https://reactjs.org/docs/installation.html)

En principe notre application a été générée, nous ponvons donc la démarrer grâce à la commande "npm start".

```start app
cd serie
npm start
```

l'application démarre sur [localhost:3000](localhost:3000). Un système de Live Reload ce met en place et met à jour notre appli automatiquement quand on sauvegarde nos changements.

Afin de tester le Live Reload, modifiez la ligne "Welcome To React" dans App.js par un autre titre puis, verifiez dans le navigateur si
les changements on bien été éffectué.

![Giphy](https://media.giphy.com/media/pt0EKLDJmVvlS/giphy.gif)

Rendez-vous à la prochaine leçon: [introduction](./introduction.md).
