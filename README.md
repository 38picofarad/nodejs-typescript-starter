# NodeJS Typescript Bolierplate

[![Actions Status](https://github.com/eunchurn/nodejs-typescript-starter/workflows/Node%20CI/badge.svg)](https://github.com/eunchurn/nodejs-typescript-starter/actions) [![Greenkeeper badge](https://badges.greenkeeper.io/eunchurn/nodejs-typescript-starter.svg)](https://greenkeeper.io/) [![Build Status](https://travis-ci.org/eunchurn/nodejs-typescript-starter.svg?branch=master)](https://travis-ci.org/eunchurn/nodejs-typescript-starter) [![codecov](https://codecov.io/gh/eunchurn/nodejs-typescript-starter/branch/master/graph/badge.svg)](https://codecov.io/gh/eunchurn/nodejs-typescript-starter)

[nodeJS](https://nodejs.org) apllication starter kit with [Typescript](https://www.typescriptlang.org/), [tslint](https://palantir.github.io/tslint/) and [prettier](https://prettier.io/), [jest](https://jestjs.io/), [travis](https://travis-ci.org/), [codecov](https://codecov.io), [husky](https://github.com/typicode/husky), [vscode](https://code.visualstudio.com/) configuration(modules resolver alias like `@libs`, `@build`).

## Files tree

```git
├── .editorconfig
├── .gitignore
├── .prettierrc
├── .travis.yml
├── .vscode
│   └── settings.json
├── LICENSE
├── README.md
├── commitlint.config.js
├── jest.config.js
├── package.json
├── src
│   ├── add.ts
│   └── index.ts
├── test
│   └── add.test.ts
├── tsconfig.json
└── tslint.json
```

## Getting started

```bash
git clone https://github.com/eunchurn/nodejs-typescript-starter.git
rm -rf .git
```

change `package.json` to your own

or

```bash
yarn
```

done
