# cep-setup-example

This is an example repo showing how to set up the Custom Elements LSP [CEP](https://www.npmjs.com/package/@genesiscommunitysuccess/custom-elements-lsp).

The `/src` directory contains an example TypeScript and [FAST](https://www.fast.design/) project.
The `/tmp` directory contains an example npm package which is installed in the main application. This is used to demonstrate the CEP being able to look at
dependency manifests - the only difference is the package is defined locally and not published to npm.

To set up the repository you need to move into the `/src` directory and run `npm run bootstrap`, and then `npm run start` to run the application.

## Setup

If you look at the `setup` branch then you can look at the required change to enable the CEP (and FAST plugin) in the `/src` app.

## Info

The `src` and `lib` packages are copies of the showcase applications from commit `79db9e4` from the [main repo](https://github.com/genesiscommunitysuccess/custom-elements-lsp).
The aim of pulling them out separately into this repo is to make the installation demo easier. This repo will not be kept up to date with those two packages over time, but will
be updated if there is a large change to the setup that this repo needs to show.

## `setup` branch

This branch contains the changeset required to do a minimal configuration of the LSP in the project. See [this video](https://www.loom.com/share/3dfdb245cbfc4fc1a166df8b19c123a5?sid=05171d67-fd36-46ab-8fa0-321542264512) for more with this setup.
