---
title: UmiJS
repo: umijs/umi
homepage: https://umijs.org
language:
  - JavaScript
license:
  - MIT
templates:
  - React
description: Pluggable enterprise-level react application framework
---

## Features

- ð¦ **Out of box**, with built-in support for react, react-router, jest, webpack, rollup, etc.
- ð **Next.js like and [full featured](https://umijs.org/guide/router.html) routing conventions**, which also supports configured routing
- ð **Plugin system**, covering every lifecycle from source code to production
- ð **High performance**, including PWA support, route-level code splitting, etc.
- ð **Support for static export**, Suitable for environments without server
- ð **Fast dev startup**, including [dll](https://umijs.org/plugin/umi-plugin-react.html#dll) support with config etc.
- ð  **Polyfill solution**, add JS and CSS polyfill with [targets](https://umijs.org/config/#targets) config, lowest to IE9
- ð **Support TypeScript**, including d.ts definition and `umi test`
- ð´ **Deep integration with [dva](https://dvajs.com/)**, including duck directory support, automatic loading of model, code splitting, etc
- âï¸ **Support MPA**ï¼based on [umi-plugin-mpa](https://github.com/umijs/umi-plugin-mpa)

## Install

Install tool

```sh
$ yarn global add umi # OR npm install -g umi
```

## Build

Create a page

```sh
$ mkdir myapp && cd myapp
$ umi generate page index
```

## Run

Start the development server

```sh
$ umi dev
```

Build and deploy

```sh
$ umi build
```

## Examples

- [Ant Design Pro](https://github.com/ant-design/ant-design-pro)
- [Antd Admin](https://github.com/zuiidea/antd-admin)
