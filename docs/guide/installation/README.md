# Installation
The preferred way to use Vue Formulate is to install via your favorite JavaScript
package manager.

## NPM
```sh
npm install @braid/vue-formulate
```

## Yarn
```sh
yarn add @braid/vue-formulate
```

## Direct download
Alternatively, if your project doesn't have a build process, you can
download the repository and manually link to the minified version:

```html
<script src="/vue-formulate/dist/formulate.min.js"></script>
```

::: warning
While you can use Vue Formulate via direct download, it is not recommended.
The remainder of the documentation assumes that you are developing in a context
that supports ES2015. In the event you do not have a build process that provides
backward support, you will need to modify the syntax of the documentation to suit
the specifics of your environment.
:::

## Add to Vue
Once Vue Formulate has been downloaded you need to install it with Vue.

```js
import Vue from 'vue'
import VueFormulate from '@braid/vue-formulate'

Vue.use(VueFormulate)
```

If you need custom configuration options, you can pass a second argument with
an object of configuration options.

```js
Vue.use(VueFormulate, options)
```