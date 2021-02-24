# Arquitectura SASS

## Table of contents

- [Description](#description)
	- [Technologies](#technologies)
- [How to use](#how-to-use)
- [License](#license)

---

## Description
Scalable SASS architecture to use in any project.

### Technologies
- SASS
- Node
- GIT

---

## How to use
It is recommended to use GIT submodules for implement in your proyect.

Example
```sh
git submodule add git@github.com:pablo247/arquitectura-sass.git /path-to-add-submodule
```

To build this boilerplate you need:
- install `node-sass` if not yet installed:
```sh
npm install -g node-sass
```
- run build command from command line:
```sh
node-sass --output-style compressed stylesheets/main.scss dist/main.css
```

---

## License

This project is open-sourced software licensed under the [MIT license](LICENSE).
