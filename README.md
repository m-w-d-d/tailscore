[![Build Status](https://travis-ci.org/Automattic/_s.svg?branch=master)](https://travis-ci.org/Automattic/_s)

Tailscore - A minimal _s (Underscores), Tailwind, Parcel & Browsersync Wordpress Theme
===

This is the [Underscores](https://underscores.me/) theme stripped down to a minimum, with [Tailwind](https://tailwindcss.com/) for CSS, [Parcel](https://parceljs.org/) to bundle it all and [Browsersync](https://browsersync.io/) used for development.

Nothing has been added asides from the above, jQuery has been removed entirely. 


## Initialize yarn and install packages

`yarn init`

`yarn`

I'm using yarn as a preference here, if you prefer npm then feel free to use that!

## Browsersync

The set up here is a presuming that you have Browsersync installed globally eg

`yarn global add browser-sync`

If you don't or prefer to install it per project then install in the usual way

Remember to change the url on the `watch` command of the package.json to your local url of choice - its set as `http://tailscore-boilerplate.local` for demo purposes here.

## Usage

Use `yarn dev` for development
Use `yarn build` to prepare for deployment

## TODO

- Get rid of jQuery remnants from the theme.
- Set up a decent production environment 
- Set up CSS folders for importing section CSS with `@apply` used for classes to avoid utility class overload
- Get rid of navigation.js default Underscores file

