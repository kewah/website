# Putain de Code !

[![Build Status](http://img.shields.io/travis/putaindecode/website.svg)](https://travis-ci.org/putaindecode/website)
[![Code Climate](http://img.shields.io/codeclimate/github/putaindecode/website.svg)](https://codeclimate.com/github/putaindecode/website)

<img align="right" alt="" src="https://raw.github.com/putaindecode/website/master/images/p!-logo--no-bubble-512--trim.png" width="128">

Code source du site [Putain de Code](http://putaindecode.fr/).
Contient tout le nécessaire pour faire fonctionner le site.
Pas de base de données à installer, pas de serveurs à configurer.

## tl;dr;

    $ git clone https://github.com/putaindecode/website.git
    $ cd website
    $ npm run init
    $ npm install
    $ npm start

## Contributions

Les articles peuvent être postés ici sous forme de PR une fois qu'on est OK dans une
issue du repo de [proposition de posts](https://github.com/putaindecode/propositions-de-posts)
(afin de pas polluer les issues techniques du site).
Si vous souhaitez voir un post écrit, ou même en écrire un, faites un tour là bas ;)

Pour contribuer au site, n'hésitez pas, en plus de lire la partie technique ci-dessous,
à lire le fichier spécifique [CONTRIBUTING.md](CONTRIBUTING.md)

---

## Développement

__Notice: Faites attention à la configuration de vos éditeurs de texte et IDE.  
Nous utilisons [`.editorconfig`](.editorconfig) pour garder une cohérence.
Respectez cela (il vous suffit d'aller sur le site [editorconfig.org/](http://editorconfig.org/)
pour télécharger le plugin adéquat pour votre éditeur.__

Ce site utilise [gulp](https://github.com/gulpjs/gulp),
il vous est donc conseillé de jeter un coup d'oeil au [README de gulp](https://github.com/gulpjs/gulp#readme)
avant d'intervenir sur le projet ;).

## Récupérer les sources du site

    $ git clone https://github.com/putaindecode/website.git
    $ cd website
    $ npm run init
    $ npm install

## Mettre à jour les sources

Lorsque vous n'avez pas travaillé sur le site depuis un petit moment, on vous conseille
d'exécuter les commandes suivantes :

    $ git pull
    $ npm install

Si vous rencontrez des erreurs lors du `git pull` (par ex. pour une histoire de
fichiers modifiés non commités), vous pouvez juste avant faire
un petit

    $ git reset --hard

__Note: cela supprimera toutes vos modifications locales sans avertissement, à
faire avec précaution.
Préférez `git stash` si vous souhaitez conserver vos modifications__.

## Lancer le site web localement

    $ npm start

Oui oui, c'est tout, vous devriez avoir le site web qui s'ouvre tout seul dans votre navigateur.
Si ce n'est pas le cas, et que vous n'avez pas d'erreurs dans votre console,
rendez-vous à l'adresse suivante: [http://localhost:4242](http://localhost:4242).


## Mise en production

La commande suivante (lorsque vous avez les droits nécessaires) va construire le site
en version optimisée, et le publier (mise à jour de la branche  `gh-pages`, qui,
grâce à GitHub, suffit à mettre en ligne le site).

    $ npm run publish

---

## Mise à jour spécifiques

### Générer le favicon

Installez [icoutils](http://www.nongnu.org/icoutils/). Par exemple sur OS X :

    $ brew install icoutils

ou

    $ npm run init-osx

Ensuite utilisez la commande suivante

    $ npm run favicon

---

## Crédits

### Auteurs et contributeurs

* [Membres de l'organisation](https://github.com/putaindecode?tab=members)
* [Liste des contributeurs](https://github.com/putaindecode/website/graphs/contributors)

### Logo & Avatar

Remerciements à toutes les personnes impliquées dans cette discussion [putaindecode/organisation/issues/4](https://github.com/putaindecode/organisation/issues/4).
Remerciement spécial à [@bloodyowl](https://github.com/bloodyowl) pour le [logo initial](https://github.com/putaindecode/website/blob/3324cbe7637dacd1f42a412c1085431a2d551928/src/assets/_images/p!-logos.png).
