# Run

```sh
$ npm install
$ npm start
```

# Developing

```sh
$ npm install -g gulp
$ gulp serve
```

## Production Build

```sh
$ gulp
```

Build and optimize the site, ready for deployment. This includes linting as well as image, script, stylesheet, and HTML optimization and minification.

## Serve Production Build

```sh
$ gulp serve:dist
```

Serve the optimized and minified version of the site for local testing.

## Deploy to gh-pages

```sh
$ gulp deploy
```

This builds for production, then deploys the dist folder to gh-pages.

## Rebuild `generated` Markdown

```sh
$ gulp generate-markdown
```

This rebuilds all markdown in the `generated` directory.

## Things to remember
I've changed the `$grid-columns` variable to 16 in the bootstrap because it wouldn't let me override it in the layouts
