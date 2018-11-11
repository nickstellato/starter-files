# Theme

## Installation

```shell
mkdir _theme_ && cd _theme_
git clone <repo address> .
npm install
```

TODO:

- Javascript minification
- Image optimization

CSS Workflow:

- Compile scss => css -> autoprefixer -> minify -> css/_.min.css -> css/_.css
- Copy all HTML files from src -> dist
- Image -> optimize -> dist/images
- JS -> minify all js files -> copy all js files to dist/js
