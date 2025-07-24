This is a [Docusaurus 2](https://docusaurus.io/) project, a modern static website generator.

## Usage

Install:

```
$ yarn
```

Develop:

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

Build:

```
$ yarn build
```

You can run the Docusaurus example using Wasmer (check out the [install guide](https://docs.wasmer.io/install)):

```bash
yarn build
wasmer run . -- --port=3000
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the docusaurus docs.


## Deploy on Wasmer Edge

The easiest way to deploy your Docusaurus app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://wasmer-edge-docusaurus-sample.wasmer.app/

First, you'll need to run `yarn build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```
