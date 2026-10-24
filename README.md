# @x12i/connectix-docs usage example

Connectix docs knowledge SDK + deployable dist/web static site. Install the package as a devDependency only; deploy dist/web for humans.

This consuming application demonstrates **list the bundled guides and read a use case** using the published npm package, pinned to `0.1.2`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

This is a documentation knowledge SDK. It is installed as a development dependency. The example lists its books and use cases, then reads the first available use-case guide from the package.

## When to use the package

- Install @x12i/connectix-docs as a development dependency so the product guides and package index are available to developers and coding assistants.
- Read the bundled connectix documentation or use-case catalog without requiring a live documentation website.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/connectix-docs)
- [Implementation monorepo](https://github.com/x12i/connectix)
- [Reviewed package source](https://github.com/x12i/connectix/tree/d024b16b986b864a76cbf533f43ae1752f459a2a/packages/connectix-docs)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
