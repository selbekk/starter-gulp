# Gulp Starter for Enonic XP

This starter gives you everything you need to get started with Enonic and Gulp.

## Initialize

Use Enonic's `toolbox.sh init-project` script to initialize your project:

```bash
./path/to/toolbox.sh init-project -n com.example.MyApp -r https://github.com/selbekk/starter-gulp.git
```

## Tasks

As a matter of convention, this starter interfaces all tasks through npm
scripts. The ones set up for you are:

```bash
npm run build       # Runs your gradle build, which in turn runs gulp
npm run deploy      # Deploys application to your local installation
npm run watch       # Continuously builds and deploys your application
```

## Gulp tasks

Since I don't what tools you want to use, I've provided a pretty bare-bones
`gulpfile`. Set it up as you see fit, with [browserify](http://browserify.org/),
[SCSS](http://sass-lang.com/) or whatever else you want.

Have a look at [gulpfile.babel.js](https://github.com/selbekk/starter-gulp/blob/master/gulpfile.babel.js)
for what's supplied by default.

Note that the Gulpfile is written in ES2015 - the newest version of JavaScript.
