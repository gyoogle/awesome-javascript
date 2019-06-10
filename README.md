# awesome-javascript

<br>

## Getting Started

<br>

### Prerequisites

| Required                                                     | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Git](https://git-scm.com/)                                  | We follow the [GitHub Flow](https://guides.github.com/introduction/flow/) |
| [Node.js](https://github.com/stunstunstun/awesome-javascript/blob/master/nodejs.org) | 10.15.0 LTS                                                  |
| [Yarn](https://yarnpkg.com/lang/en/)                         | 1.12.3 or above                                              |

<br>

### Install Node, Yarn

The project manages the version of node through `nvm`.

```
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
$ command -v nvm
$ nvm install 10.15.0
$ which node
$ npm install -g yarn
```

In the project root as follows are performed through the `.nvmrc`

```
$ nvm use
...
```

<br>

## Yarn CLIs

<br>

### Install project

```
$ nvm use
$ yarn install
```

<br>

### Test

```
$ yarn test
```