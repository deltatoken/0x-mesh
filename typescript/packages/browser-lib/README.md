## @0x/mesh-browser-lib

This is an internal package used to share code used to provide Typescript and Javascript bindings for browser
based mesh nodes. This package should not be used outside of the mesh codebase. Instead, the @0x/mesh-browser
and @0x/mesh-browser-lite packages are designed to be used externally.

## Installation

```bash
yarn add @0x/mesh-browser-lib
```

If your project is in [TypeScript](https://www.typescriptlang.org/), add the following to your `tsconfig.json`:

```json
"compilerOptions": {
    "typeRoots": ["node_modules/@0x/typescript-typings/types", "node_modules/@types"],
}
```

## Contributing

If you would like to contribute bug fixes or new features to the client, checkout the [0xproject/0x-mesh](https://github.com/0xProject/0x-mesh) project and use the below commands to install the dependencies, build, lint and test your changes.

### Install dependencies

```bash
yarn install
```

### Build

```bash
yarn build
```

### Clean

```bash
yarn clean
```

### Lint

```bash
yarn lint
```