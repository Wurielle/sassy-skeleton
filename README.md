# [Sassy-Skeleton](http://noahfenghom.com/sassy-skeleton)

Sassy Skeleton is an unofficial Sass (and not SCSS)  version of [Dave Gamache's](https://twitter.com/dhg) Skeleton Framework. It currently features a stable version of Skeleton 2.0.4.

Check out <http://getskeleton.com> for the original documentation and details.

## Getting started

Compiling Sass:
- using Sass:

```
sass path/to/file/input.sass path/to/file/output.css
```

Or simply:

```
sass --watch path/to/directory/sass:path/to/directory/css
```

e.g. in this case:

```
sass --watch sass:export
```

- using COMPASS:

```
compass init
```

Edit your config.rb (e.g. here's mine):

```
require 'compass/import-once/activate'
# Require any additional compass plugins here.

# Set this to the root of your project when deployed:
http_path = "/"
css_dir = "export"
sass_dir = "sass"

# You can select your preferred output style here (can be overridden via the command line):
# output_style = :expanded or :nested or :compact or :compressed

# To enable relative paths to assets via compass helper functions. Uncomment:
relative_assets = true

# To disable debugging comments that display the original location of your selectors. Uncomment:
# line_comments = false


# If you prefer the indented syntax, you might want to regenerate this
# project again passing --syntax sass, or you can uncomment this:
# preferred_syntax = :sass
# and then run:
# sass-convert -R --from scss --to sass sass scss && rm -rf sass && mv scss sass

```

Now compile:

```
compass compile
```

Or watch:

```
compass watch
```


### What's in the download?

The download includes Sassy Skeleton's Sass, Skeleton's CSS (2.0.4), Normalize CSS as a reset, ~~a sample favicon,~~ and an index.html as a ~~starting point~~ demo presentation.

```
Sassy-Skeleton/
├── index.html
├── export/
│   └── main.css
├── original/
│   └── css/
│	    ├── normalize.min.css
│	    └── skeleton.css
└── sass/
    ├── _normalize.scss
    ├── _removeme.sass
    ├── _variables.sass
    ├── main.sass
    └── ui/
        ├──_all.sass
        ├──_base.sass
        ├──_buttons.sass
        ├──_clearing.sass
        ├──_code.sass
        ├──_forms.sass
        ├──_grid.sass
        ├──_links.sass
        ├──_lists.sass
        ├──_misc.sass
        ├──_mq.sass
        ├──_spacing.sass
        ├──_tables.sass
        ├──_typography.sass
        └──_utilities.sass

```


### Why it's awesome

Skeleton is lightweight and simple. It styles only raw HTML elements (with a few exceptions) and provides a responsive grid. Nothing more.
- ~~Around 400 lines~~ Segmented files of Sass unminified and with comments
- It's a starting point, not a UI framework
- ~~No compiling or installing...just vanilla CSS~~ Requires a Sass compiler (see Getting started)


## Browser support

- Chrome latest
- Firefox latest
- Opera latest
- Safari latest
- IE latest

The above list is non-exhaustive. Skeleton works perfectly with almost all older versions of the browsers above, though IE certainly has large degradation prior to IE9.


## License

All parts of Skeleton are free to use and abuse under the [open-source MIT license](https://github.com/dhg/Skeleton/blob/master/LICENSE.md).


## Extensions

The following are extensions to Skeleton built by the community. They are not officially supported, but all have been tested and are compatible with v2.0 (exact release noted):
- [Skeleton on LESS](https://github.com/whatsnewsaes/Skeleton-less): Skeleton built with LESS for easier replacement of grid, color, and media queries. (Last update was to match v2.0.1)
- [Skeleton on Sass](https://github.com/whatsnewsaes/Skeleton-Sass): Skeleton built with Sass for easier replacement of grid, color, and media queries. (Last update was to match v2.0.1)


## Colophon

Skeleton was built using [Sublime Text 3](http://www.sublimetext.com/3) and designed with [Sketch](http://bohemiancoding.com/sketch). The typeface [Raleway](http://www.google.com/fonts/specimen/Raleway) was created by [Matt McInerney](http://matt.cc/) and [Pablo Impallari](http://www.impallari.com/).


## Acknowledgement

Skeleton was created by [Dave Gamache](https://twitter.com/dhg) for a better web.
