# Microservices : Global Common Components

Common components to use with Express projects

## Publishing to NPM

The first (manual) publish to `npm` should specify if the package visibility is public

`npm publish --access public`

## Versioning

Github workflow will only update minor version.

For hotfixes (patch version) and breaking changes (major version), manually publish an update.

(this can be automated with `semver`)
