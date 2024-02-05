# moonrepo Monorepo Template Configuration Files

## babel

[babel.config.js](./babel.config.js)

## eslint

[.eslintignore](./.eslintignore)
[.eslintrc.js](./.eslintrc.js)

## git

[.gitattributes](./.gitattributes)
[.github](./.github)
[.gitignore](./.gitignore)

## Github Workflows

[.github/workflows/ci.yml](.github/workflows/ci.yml)

## moon & proto

[.moon](./.moon)
[.prototools](./.prototools)

### mooon Tasks & tags

#### tags

- [astro](.moon/tasks/tag-astro.yml)
- [packemon](.moon/tasks/tag-packemon.yml)
- [vite](.moon/tasks/tag-vite.yml)
- [vitest](.moon/tasks/tag-vitest.yml)

#### tasks

Tasks for all projects are defined in [.moon/tasks/node.yml](./.moon/tasks/node.yml)

- format
- format-write
- lint | 📖 [eslint guide](https://moonrepo.dev/docs/guides/examples/eslint)
- test | 📖 [jest guide](https://moonrepo.dev/docs/guides/examples/jest)  
- typecheck | 📖 [typescript guide](https://moonrepo.dev/docs/guides/examples/typescript)

Tasks that only apply for `library` type projects are at [.moon/tasks/node-library.yml](./.moon/tasks/node-library.yml)

- build | 📖 [packemon guide](https://moonrepo.dev/docs/guides/examples/packemon)

## Node / npm / yarn

[.npmrc](./.npmrc)
[.nvmrc](./.nvmrc)
[.yarnrc.yml](./.yarnrc.yml)

## prettier

[.prettierignore](./.prettierignore)
[prettier.config.js](./prettier.config.js)

## IDEs

[.vscode](./.vscode)

## typescript

[tsconfig.eslint.json](./tsconfig.eslint.json)
[tsconfig.json](./tsconfig.json)
[tsconfig.options.json](./tsconfig.options.json)
