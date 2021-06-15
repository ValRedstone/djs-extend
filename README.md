# DJS-Extend est un nouveau module npm

Le lien du serveur support est [içi](https://discord.gg/9F9ECNMzv9)

La page du module est [içi](https://www.npmjs.com/package/djs-extend)

Il y a peu de fonctions pour le moment mais je vais vous les expliquer.

```js
const { Client } = require("discord.js"); //Module nécessaire au fonctionnement du bot.
const DJSE = require("djs-extend"); //Définit le module.

const bot = new Client(); //Définit le client.

DJSE.Login(bot, "YOUR BOT TOKEN"); //Permet de connecter votre bot discord avec cette fonction.

console.log(DJSE.version); //Envoie dans la console la version du module.
```