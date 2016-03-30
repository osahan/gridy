# Gridy
12 Column responsive flexbox CSS grid system.


##Getting Started

[Download Gridy](https://github.com/osahan/gridy/archive/master.zip) and include the CSS in the of your site:

```html
<link rel="stylesheet" href="/dist/gridy.min.css">
```

Alternatively, you can install Gridy with [Bower](http://bower.io/) or [NPM](https://www.npmjs.com/).

###Bower

```shell
$ bower install gridy
```
###npm

```shell
$ npm install gridy
```

##Customizing with Sass

If you’re familiar with [SASS](http://sass-lang.com/) you can easily customize Gridy, its pretty easy to use your own classNames, grid gutters and even viewport breakpoints.

Import Files & Customize

```scss
$gridy-classname-prefix: "" !default;
$gridy-container-abbr: "container" !default;
$gridy-block-abbr: "grid" !default;
$gridy-column-abbr: "col" !default;
$gridy-grid-gutter: 20px !default;

$gridy-breakpoint-list: (
    xs: (0px, 320px, 100%, 20px),
    sm: (321px, 768px, 100%, 20px),
    md: (769px, 1023px, 100%, 20px),
    lg: (1024px, 1439px, 1024px, 20px),
    xl: (1440px, 100%, 1200px, 20px)
) !default;

@import "gridy/dist/app/gridy";
```

## License

Licensed under the MIT license, http://www.opensource.org/licenses/mit-license.php