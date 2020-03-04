# vue-netlify

[![Netlify Status](https://api.netlify.com/api/v1/badges/3b5ffbc9-f3ad-44f0-b724-650aff5f8aa9/deploy-status)](https://app.netlify.com/sites/vue-netlify-test/deploys)

For this VueJS webpack project. Demo for hide API key from git. Just inject by cmd line as below Build Setup reference.

The App is live [here](https://vue-netlify-test.netlify.com)



## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev -- --env.HELLO_KEY="key from here not in git - dev"

# build for production with minification
npm run build -- --env.HELLO_KEY="key from here not in git - production"

# build for production and view the bundle analyzer report
npm run build --report

# serve production build in local
node index.js

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
