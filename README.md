# Node Boilerplate

A minimal Node.js project boilerplate with ESLint, Jest, and a pre-commit lint hook.

[![CI](https://github.com/nadimtuhin/node-boilerplate/actions/workflows/ci.yml/badge.svg)](https://github.com/nadimtuhin/node-boilerplate/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Features

- Jest for testing
- ESLint for linting
- Husky pre-commit hook that runs ESLint on staged files
- CI via GitHub Actions (Node 20 & 22)

## Getting Started

```bash
git clone https://github.com/nadimtuhin/node-boilerplate.git my-project
cd my-project
yarn install
```

## Usage

```bash
yarn test   # run tests (watch mode locally, single run on CI)
yarn lint   # lint src/ with ESLint
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## License

[MIT](LICENSE) © 2024 nadimtuhin
