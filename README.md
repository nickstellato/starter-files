# Theme

## Installation

```shell
mkdir _theme_ && cd _theme_
git clone <repo address> .
npm install
npm start
```

TODO:

- Need to copy the index.html file from src -> dist when there is a saved change.

Notes:

- A user can clone the repo and start a development server.
- I want this to be the quickest way to get a folder structure for HTML, CSS, JS, and Images
- I want this to be reusable
- I also want it to be a way to get from idea to playground as quickly as possible.

Ideas:

- Serve dist folder with auto-reload

CSS Workflow:

- Compile scss => css -> autoprefixer -> minify -> css/_.min.css -> css/_.css
- Copy all HTML files from src -> dist
- Image -> optimize -> dist/images
- JS -> minify all js files -> copy all js files to dist/js
