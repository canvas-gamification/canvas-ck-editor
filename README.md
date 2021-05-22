# CKEditor 5 Build for Canvas Gamification

This repository presents a CKEditor 5 editor build generated specifically for the Canvas Gamification UI. When a change is pushed to master with a new version number in the `package.json` the build is automatically published to [npmjs](https://www.npmjs.com/package/@canvas-gamification/ckeditor5).

## Installation

In order to rebuild the application you need to install all dependencies first. To do it, open the terminal in the project directory and type:

```
npm install
```

Make sure that you have the `node` and `npm` installed first. If not, then follow the instructions on the [Node.js documentation page](https://nodejs.org/en/).

## Adding or removing plugins

Now you can install additional plugins in the build. Just follow the [adding a plugin to an editor tutorial](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/installing-plugins.html#adding-a-plugin-to-an-editor)

## Rebuilding editor

If you have already done the [installation](#installation) and [adding or removing plugins](#adding-or-removing-plugins) steps, you're ready to rebuild the editor by running the following command:

```
npm run build
```

This will build the CKEditor 5 to the `build` directory. 
