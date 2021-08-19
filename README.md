<div align="center" style="background-color:'#00AAAE'">
<img src="./static/img/docusaurus-lockscreen.gif" height="200"> <br>
  <strong>Docusaurus Lockscreen Starter</strong>
</div>
<div align="center">
  A <code>starter</code> to create docusaurus with lockscreen page
</div>

<br />

<div align="center">
  <!-- Docusaurus Version -->
  <img src="https://img.shields.io/badge/docusaurus-v2.0-green" 
    alt="Docusaurus version" />
  <!-- React Version -->
  <img src="https://img.shields.io/badge/react-v17.0-purple" 
    alt="React version" />
</div>

### Table of Contents
- [Demo](#demo)
- [How to Use](#how-to-use)
- [How to Create](#how-to-create)
- [Website Information](#website-information)
  - [Installation](#installation)
  - [Local Development](#local-development)
  - [Build](#build)
  - [Deployment](#deployment)

## Demo

Please view demo **[here](http://coroo.github.io/docusaurus-lockscreen-starter/)**.

```
Pass: secret
```

## How to Use

To use this documentation, you can easily use `fork`.

## How to Create

For ideas & how to create documentation please refer to this [medium](https://kuncorowicaksono.medium.com/docusaurus-access-restriction-lockscreen-github-page-ed80f4971a7).

## Website Information

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

```
$ GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
