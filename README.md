<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

  <p align="center">A progressive <a href="http://nodejs.org" target="blank">Node.js</a> framework for building efficient and scalable server-side applications, heavily inspired by <a href="https://angular.io" target="blank">Angular</a>.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/v/@hyman/schematics.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/l/@hyman/schematics.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/dm/@hyman/schematics.svg" alt="NPM Downloads" /></a>
<a href="https://gitter.im/nestjs/nestjs-cli?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=body_badge"><img src="https://badges.gitter.im/nestjs/nestjs.svg" alt="Gitter" /></a>

## Description

In order to help people manage their projects, the CLI tool has been created. It helps on many grounds at once, from scaffolding the project to build well-structured applications. The Nest CLI is based on the [@angular-devkit](https://github.com/angular/devkit) package. Also, there're special schematics that are dedicated to the Nest development [@hyman/schematics](https://github.com/nestjs/schematics).


## Installation
### NPM:

```
$ npm install -g @hyman/schematics
```

### Docker:
```
$ docker pull nestjs/cli[:version]
$ docker run -it -rm -p 3000:3000 -v $(pwd)/workspace nestjs/schematics[:version]
```

### GIT:
```
$ git clone https://github.com/nestjs/schematics.git <project>
$ cd <project>
```

With your Node runtime:
```
$ npm install
$ npm link
```

With Docker:

```
$ docker build -t nestjs/schematics .
```

## Usage

Learn more in the [official documentation](https://docs.nestjs.com/).

## Stay in touch

* CLI Author - [Thomas Ricart](https://github.com/ThomRick) and [Kamil Mysliwiec](https://github.com/kamilmysliwiec)
* Website - [https://nestjs.com](https://nestjs.com/)
* Twitter - [@nestframework](https://twitter.com/nestframework)
