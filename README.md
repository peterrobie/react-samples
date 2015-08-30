React.js Examples
========================

This repo contains a bunch of React.js examples. No server side code, just client-side React components. 

> Make sure you have NPM and Webpack installed before getting started.

### Getting started

* Install: `npm install`
* Build: `webpack --watch`
* Start: `open src/index.html`

### Create new samples

* Fork this repo
* Create a sample module, e.g. `src/js/mysample/mysample-view.js`
* Add your sample to `src/js/app.js` by adding: `samples.push(require('./mysample/mysample-view'));`

### License

MIT
