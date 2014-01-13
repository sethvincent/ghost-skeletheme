# ghost-skeletheme

A starter theme for the [Ghost](http://github.com/TryGhost/Ghost) blogging platform.

## Why

This starter theme makes use these three css modules to ease the development process:

- [npm-css](https://github.com/defunctzombie/npm-css), a module for `@import`ing css from the `node_modules` folder.
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

## License

MIT.