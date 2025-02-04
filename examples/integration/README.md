# Astro Starter Kit: Integration Package

This is a template for an Astro integration. Use this template for writing integrations to use in multiple projects or publish to NPM.

```
npm create astro@latest -- --template integration
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/integration)


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── index.ts
├── tsconfig.json
├── package.json
```

The `index.ts` file is the "entry point" for your integration. Export your integration in `index.ts` to make them importable from your package.

## 🧞 Commands
All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm link`              | Registers this package locally. Run `npm link my-integration` in an Astro project to install your integration
| `npm publish` | [Publishes](https://docs.npmjs.com/creating-and-publishing-unscoped-public-packages#publishing-unscoped-public-packages) this package to NPM. Requires you to be [logged in](https://docs.npmjs.com/cli/v8/commands/npm-adduser)
