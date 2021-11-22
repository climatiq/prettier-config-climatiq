# Climatiq Prettier Config

This package provides Climatiq's ESLint configuration as a base config for any project in Climatiq and requires `prettier`

## Installation

To install this config and the peerDependencies (note the `npx` command). If you are using yarn, the command will detect it and will prompt to use yarn command instead.

```bash
npx install-peerdeps --dev @climatiq/prettier-config
```

Now create a Prettier configuration file, `.prettierrc` for your project that extends Climatiq's rules:

```prettier
"@climatiq/prettier-config"
```

Now run `npx prettier path/to/files` to test if everything works as expected.

## Editor/IDE integration

Running Prettier from your IDE or Editor is very useful as Prettier will fix formatting on-the-fly. [Read this guide for more instructions](https://prettier.io/docs/en/editors.html) 