# cypress-gh-action-split-install ![status](https://github.com/bahmutov/cypress-gh-action-split-install/workflows/tests/badge.svg?branch=master)

> Example using [npm-install](https://github.com/bahmutov/npm-install) and manual [Cypress installation](https://github.com/cypress-io/github-action) inside GH Action.

See [.github/workflows/tests.yml](.github/workflows/tests.yml)

First, only NPM dependencies are installed (without Cypress binary).
Then Cypress binary is installed, used to run end-to-end tests, and cached.

![Action steps](images/install-cypress.png)
