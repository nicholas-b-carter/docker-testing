# react-redux-universal-boilerplate

[![Greenkeeper badge](https://badges.greenkeeper.io/nicholas-b-carter/docker-testing.svg)](https://greenkeeper.io/)

Another web app boilerplate, based on react and redux.

This repo is a **Work in Progress**

Includes:
* Internationalization (i18n) out-of-the-box
* Builds the codebase for: server, browser or cordova
* Hot Reloading

Uses:
* React
* React Router
* React Intl
* Redux
* Docker
* Cordova
* Webpack

## Requirements

* NodeJS
* NPM

## Instalation

```
git clone https://github.com/cusspvz/react-redux-universal-boilerplate my-webapp
cd my-webapp
npm install
```

## Development

```
npm run dev
```

## Building

### Docker resources server

Building:
```
docker build -t oracle-docker:latest .
```

Publishing:
```
docker push your-username/my-webapp
```

### Cordova

```
npm run build-cordova
```

**TODO**: Add zip handler for PGB service
