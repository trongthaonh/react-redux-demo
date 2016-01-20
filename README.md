
Quick setup for new performance orientated, offline–first React.js applications featuring Redux, hot–reloading, PostCSS, react-router, ServiceWorker, AppCache, FontFaceObserver and Mocha.

-----

## Features

- Using [**react-transform-hmr**](https://github.com/gaearon/react-transform-hmr), your changes in the CSS and JS get reflected in the app instantly without refreshing the page. That means that the **current application state persists** even when you change something in the underlying code! For a very good explanation and demo, watch Dan Abramov himself [talking about it at react-europe](https://www.youtube.com/watch?v=xsSnOQynTHs).

- [**Redux**](https://github.com/rackt/redux) is a much better implementation of a flux–like, unidirectional data flow. Redux makes actions composable, reduces the boilerplate code and makes hot–reloading possible in the first place. For a good overview of redux, check out the talk linked above or the [official documentation](https://gaearon.github.io/redux/)!

- [**Babel**](http://babeljs.io/) is a modular JavaScript transpiler that helps to use next generation JavaScript and more, like transformation for JSX, hot loading, error catching etc. Babel has a [solid ecosystem of offical preset and plugins](https://github.com/babel/babel/tree/master/packages).

- [**PostCSS**](https://github.com/postcss/postcss) is like Sass, but modular and capable of much more. PostCSS is, in essence, just a wrapper for plugins which exposes an easy to use, but very powerful API. While it is possible to [replicate Sass features](https://github.com/jonathantneal/precss) with PostCSS, PostCSS has an [ecosystem of amazing plugins](http://postcss.parts) with functionalities Sass cannot even dream about having. See [this talk](http://mxs.is/pctalk) for a short introduction to PostCSS.

- **Unit tests** should be an important part of every web application developers toolchain. [Mocha](https://github.com/mochajs/mocha) checks your application is working exactly how it should without you lifting a single finger. Congratulations, you just won a First Class ticket to world domination, fasten your seat belt please!

- [**react-router**](https://github.com/rackt/react-router) is used for routing in this boilerplate. react-router makes routing easy to do and takes care of most of the work. (except you have to define your routes yourself) You can find the documentation right  [here](https://github.com/rackt/react-router/blob/master/doc/00%20Guides/0%20Overview.md).

- [**ServiceWorker**](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) and [**AppCache**](http://www.html5rocks.com/en/tutorials/appcache/beginner/) make it possible to use your application offline. As soon as the website has been opened once, it is cached and available without a network connection. See [this talk](http://mxs.is/swtalk) for an explanation of the ServiceWorker used in this boilerplate. [**`manifest.json`**](https://developer.chrome.com/multidevice/android/installtohomescreen) is specifically for Chrome on Android. Users can add the website to the homescreen and use it like a native app!

Made with :heart: by [Max Stoiber](https://twitter.com/mxstbr)!