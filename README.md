# Avanced React Concepts - Case Study

- yarn
- Atomic Design
- Monorepo with Lerna
- Story Book
- Automated Tests

## Todo

- [ ] add CHROMATIC regression test to ci
- [ ] configure netlify to build and deploy story books

## Instalation

Open the terminal on the root folder and type the following.

To install all packages at once:

```sh
yarn
```

To build all packages at once:

```sh
yarn build
```

## Testing on the Playground

Needs to be installed first.

Open the terminal on the playground folder and run the following command:

```sh
yarn dev
```

## Development Mode

To install all the dependencies and start the development server with hot reloadings go the the root folder of the project and run the following:

```sh
yarn && yarn dev
```

## Tests

Open the terminal on the root folder and type the following.
Obs. Needs to be installed first. See "Instalation" section of this README.

```sh
yarn test
```

## Publishing

To publish the packages to NPM using lerna:

1.  Create an account on NPM.
2.  open the terminal on the root folder.
3.  Login on NPM with the command `npm login`
4.  Pubish to NPM using the command `yarn publish`
    1. Chose the version
    2. Accept the publish

The process above will commit changes on git (but don't push changes to remote) using the version number as commit message.
