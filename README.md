# Générateur de certificat de déplacement

## Notes du fork

Ce fork permet le pré-remplissage du formulaire lorsqu'il est utilisé sur un même ordinateur.

**Note importante:** les données du formulaire ne sont jamais supprimées de l'ordinateur générant le formulaire, il est donc fortement conseiller de l'utiliser sur une machine sûre et personnelle.

Pour éviter tout risque de sécurité, utilisez le formulaire officiel: https://media.interieur.gouv.fr/deplacement-covid-19/

## Développer

### Installer le projet

```console
$ git clone https://github.com/lab-mi/deplacement-covid-19.git
$ cd deplacement-covid-19
$ npm i
$ npm start
```

### Générer le code de production

```console
$ npm run build
```

Le code à déployer sera dans le dossier `dist`

## Crédits

Ce projet a été réalisé à partir d'un fork du dépôt [covid-19-certificate](https://github.com/nesk/covid-19-certificate) de [Johann Pardanaud](https://github.com/nesk).

Les projets open source suivants ont été utilisés pour le développement de ce
service :

- [PDF-LIB](https://pdf-lib.js.org/)
- [qrcode](https://github.com/soldair/node-qrcode)
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/license)
