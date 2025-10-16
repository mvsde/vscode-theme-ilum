# Contributing

## Create a release

Bump the [package version](https://docs.npmjs.com/cli/commands/npm-version):

```sh
npm version …
```

Publish the new version with [vsce](https://github.com/microsoft/vscode-vsce):

```sh
npx @vscode/vsce@latest publish
```
