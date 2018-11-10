# react-monorepo-lerna-yarn-workspaces

> Testing a Lerna React Monorepo setup with Yarn Workspaces.

See: 

- https://github.com/facebook/create-react-app/issues/1333#issuecomment-435996800
- https://github.com/facebook/create-react-app/issues/1333#issuecomment-436003963

## Usage

```shell
$ yarn config set workspaces-experimental true
$ yarn install
$ lerna run transpile
$ cd apps/app-foo
$ yarn start
```
