# markdown-it-katex-newcommand
Plugin markdown-it for katex rendering with ability to add global \newcommand 

## Installation

```bash
yarn add markdown-it-katex-newcommand
```

## Basic

```js
var md = require('markdown-it')(),
    mkn = require('markdown-it-katex-newcommand');

md.use(mkn);
```
