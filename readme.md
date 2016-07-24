# Grid Element

![Grid Element logo](https://cdn.rawgit.com/charbelrami/grid-element/master/grid-element-logo.svg)

**[New documentation page!](http://charbelrami.github.io/grid-element-docs)**

## Development

```sh
$ cd grid-element
```

### Install dependencies

```sh
$ bower i && npm i
```

- Installs bower local dependencies
- Installs npm local dependencies

### Lint elements

```sh
$ npm run lint
```

### Run local server

```sh
$ npm run serve
```

### Bump version

```sh
$ npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
```

- Ensures the working tree is clean
- Lints elements
- Bumps the version in package.json
- Updates the git index to match the working tree
- Creates a git tag
- Pushes all the refs, including annotated tags
