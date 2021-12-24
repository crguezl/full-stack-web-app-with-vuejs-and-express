# Tab Tracker
A Vue.js / Express.js web application for keeping track of guitar tabs

# Setup

You need to have Node Js installed: https://nodejs.org/en/

You must at least have **NODE version 8.2.1**

Don't know how to install different version of node?  Try this: https://github.com/tj/n

I suggest you install the following that I use in the video:

VSCode: https://code.visualstudio.com/

ITerm2: https://www.iterm2.com/ (Mac Only)

Git: https://git-scm.com/

## Comments 2021

- Install v8.2 of node. It fails with v16.13
- The vue-cli used in the video is 2.8.2. Use `npx vue` instead of `vue`
  
```
➜  tab-tracker git:(main) ✗ npx vue --version
2.8.2
➜  tab-tracker git:(main) npx vue list

  Available official templates:

  ★  browserify - A full-featured Browserify + vueify setup with hot-reload, linting & unit testing.
  ★  browserify-simple - A simple Browserify + vueify setup for quick prototyping.
  ★  pwa - PWA template for vue-cli based on the webpack template
  ★  simple - The simplest possible Vue setup in a single HTML file
  ★  webpack - A full-featured Webpack + vue-loader setup with hot reload, linting, testing & css extraction.
  ★  webpack-simple - A simple Webpack + vue-loader setup for quick prototyping.
  ```

### Client - Terminal A
```
cd client
npm install
npm start
```

### Server - Terminal B
```
cd server
npm install
npm start
```
