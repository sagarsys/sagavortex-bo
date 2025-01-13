This is a headless CMS for an image gallery website, where you can upload images to Cloudinary, manage categories, tags, users and posts.

## 🚀 Getting started

This project was built on top of [Strapi](https://www.strapi.io).
Strapi comes with a full-featured [Command Line Interface](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html) (CLI) which lets you scaffold and manage your project in seconds.

### `install`
Start by installing deps, with Node version 12-16

```npm
npm install
# or
yarn
```

## Postgres

A valid postgres DB is required, refer to `config/database.js` for connection details.

## ENV File
Duplicate the `.env.example` file to create a valid `.env` file with the required API keys.

Most notably, a valid cloudinary API key is required to connect to the cloudinary APIs.

## AVAILABLE COMMANDS

### `develop`

Start your CMS application with autoReload enabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start the CMS application with autoReload disabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build the admin panel. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

```
npm run build
# or
yarn build
```
