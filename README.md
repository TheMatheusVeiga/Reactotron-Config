# Reactotron Configuration Guide
> A simple guide for configuring the reactotron in your redux based projects.



[![Build Status][travis-image]][travis-url]


## Installation

Let's install Reactotron as a dev dependency.

```sh
npm i --save-dev reactotron-react-js
```



I like a separate file for initializing. Create src/ReactotronConfig.js in your editor of choice and paste this:

```sh
import Reactotron from 'reactotron-react-js'

Reactotron
  .configure() // we can use plugins here -- more on this later
  .connect() // let's connect!
```



Finally, we import this on startup in src/index.js on line 1:

```sh
import './ReactotronConfig'
```



## Integrating with Redux

```sh
npm i --save-dev reactotron-react-js
```





## Credits

Reactotron is developed by [Infinite Red](https://infinite.red), [@rmevans9](https://github.com/rmevans9), and 70+ amazing contributors! Special thanks to [@skellock](https://github.com/skellock) for originally creating Reactotron while at Infinite Red.

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
