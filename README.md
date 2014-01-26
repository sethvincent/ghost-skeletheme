# ghost-skeletheme

A starter theme for the [Ghost](http://github.com/TryGhost/Ghost) blogging platform.

## Why

This starter theme makes use of these three css modules to ease the development process:

- [rework-npm-cli](https://github.com/sethvincent/rework-npm-cli), a module for `@import`ing css from the `node_modules` folder using rework-npm.
- [myth](https://github.com/segmentio/myth), a preprocessor module that generates cross-browser css based on [rework](https://github.com/reworkcss/rework).
- [clean-css](https://github.com/GoalSmashers/clean-css), a module that minifies css files.

It also uses [browserify](http://github.com/substack/node-browserify) to bundle javascript modules.

## Install

Install by cloning the git repository into the themes folder of your ghost blog, `your-ghost-directory/content/themes/`.

```
git clone https://github.com/sethvincent/ghost-skeletheme.git
```

### Dependencies:

Install the dependencies of the theme:

```
npm install
```

## Usage

Edit the style.css and index.js files in the src directory.

Run `npm run bundle` to generate the css and js bundles that are then places in the assets/css and assets/js directories.

You can run just the css bundler with `npm run bundle-css` and just the js bundler with `npm run bundle-js`.

Run `npm start` to watch the css and js files in the `src` folder for changes and automatically regenerate the bundles.

## License

MIT.