# Theme

## Installation

```shell
git clone <repo address> .
npm install
```

After `npm install` runs, the server will start with the provided code.

TODO:

- Javascript minification
- Image optimization

CSS Workflow:

- Compile scss => css -> autoprefixer -> minify -> css/_.min.css -> css/_.css
- Copy all HTML files from src -> dist
- Image -> optimize -> dist/images
- JS -> minify all js files -> copy all js files to dist/js
