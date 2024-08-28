---
sidebar_position: 1
---

# Introduction au Tutoriel

Découvrons **Docusaurus en moins de 5 minutes**.

## Pour commencer

Commencez par **créer un nouveau site**.

Ou **essayez Docusaurus immédiatement** avec **[docusaurus.new](https://docusaurus.new)**.

### Ce dont vous aurez besoin

- [Node.js](https://nodejs.org/en/download/) version 18.0 ou supérieure :
  - Lors de l'installation de Node.js, il est recommandé de cocher toutes les cases liées aux dépendances.

## Générer un nouveau site

Générez un nouveau site Docusaurus en utilisant le **modèle classique**.

Le modèle classique sera automatiquement ajouté à votre projet après avoir exécuté la commande :

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
