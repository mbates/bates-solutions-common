# Bates Solutions : Common

## Publishing to NPM

First publish to `npm` should specify if the package will be public

`npm publish --access public`

`npm run pub` is **NOT** production grade code.

## Versioning

Github workflow will only update minor version.

For hotfixes (patch version) and breaking changes (major version), manually publish an update.

(this can be automated with `semver`)
