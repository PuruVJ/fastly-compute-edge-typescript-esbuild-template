# Compute@Edge TypeScript ESBuild Starter kit

A TypeScript starter kit for building a web application using the Compute@Edge platform.

## Features

- TypeScript
- Blazing fast ⚡️
- ESBuild
- PNPM (Although feel free to use other package manager) 🔥
- Embed HTMl CSS files by importing them as ES Modules.

## Installing

Recommended to scaffold the project with [aho](https://github.com/egoist/aho)

```sh
# PNPM
pnpm dlx aho PuruVJ/fastly-compute-edge-typescript-esbuild-template [destination]

# NPM
npx aho PuruVJ/fastly-compute-edge-typescript-esbuild-template [destination]
```

## Starting Local server

Starts local Compute@Edge server. Any changes to `src` folder restarts the server

> **NOTE:** If there's a compilation error from ESBuild, the server will crash and you'll need to restart. Recommend using pm2 for this case (https://www.npmjs.com/package/pm2)

```sh
# PNPM
pnpm watch

# NPM
npm run watch
```

## Build and Compile to WASM

Build the project and compile to WASM for deploying

```sh
# PNPM
pnpm build

# NPM
npm run build
```

## Deploying

Builds the project and deploys in just one command

```sh
# PNPM
pnpm deploy

# NPM
npm run deploy
```

# License

MIT © [PuruVJ](https://twitter.com/puruvjdev)
