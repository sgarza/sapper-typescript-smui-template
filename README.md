# sapper-typescript-smui-template

The default [Sapper](https://github.com/sveltejs/sapper#webpack) template using webpack, with included support for [SMUI](https://github.com/hperrin/svelte-material-ui) and [TypeScript](https://www.typescriptlang.org/).

## Getting started

### Using `degit`

[`degit`](https://github.com/sgarza/sapper-typescript-smui-template) is a scaffolding tool that lets you create a directory from a branch in a repository.

```bash
npx degit "https://github.com/sgarza/sapper-typescript-smui-template" my-app
```

### Using GitHub templates

Alternatively, you can use GitHub's template feature with this repository.

### Running the project

Running the app is as usual:

```bash
cd my-app
npm install # or yarn
npm run dev
```

Open up [localhost:3000](http://localhost:3000) and start clicking around.

## Usage

At the moment, you will get a standard sapper app and one additional SMUI Button. As explained in the SMUI repository it is recommended to install each component on its own. So currently you will only be able to use buttons.

If you want to install further components, just do

```bash
npm install --save-dev @smui/component-name
```

**Be sure to add `--save-dev` or `-D` to add those components as dev-Dependencies. They will not work if you install them as normal dependencies.**
