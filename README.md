
# typeface-exo-2

Temperary npm package until [Google Font issue 1500](https://github.com/google/fonts/issues/1500) is resolved.

The CSS and web font files to easily self-host “Exo 2”.
This is a fork from [typefaces](https://github.com/KyleAMathews/typefaces) that support [font-variant-numeric: tabular-nums;](https://developer.mozilla.org/en-US/docs/Web/CSS/font-variant-numeric).

# IMPORTANT #

Due to lack of time, only the regular (_exo-2-latin-400_ and _exo-2-latin-400italic_) font weight has `tnum` support.
If you use this package (because Google Font are slow to update)
and you need other font-weight, then create an issue and I will add it to this repo.

# The Author #

Exo 2 is created by [Natanael Gama](http://www.ndiscovered.com/).
Please consider donating to him. [Donate to Author via paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=DFHFU7BUVHEG4)

## Install

`npm install --save @dotnetcarpenter/typeface-exo-2`

## Use

Typefaces assume you’re using webpack to process CSS and files. Each typeface
package includes all necessary font files (woff2, woff, eot, ttf, svg) and
a CSS file with font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files. Many tools built
with Webpack will work out of the box with Typefaces such as [Gatsby](https://github.com/gatsbyjs/gatsby)
and [Create React App](https://github.com/facebookincubator/create-react-app).

To use, simply require the package in your project’s entry file e.g.

```javascript
// Load Exo 2 typeface
require('typeface-exo-2')
```

## About the Typefaces project.

Our goal is to add all open source fonts to NPM to simplify using great fonts in
our web projects. We’re currently maintaining 862 typeface packages
including all typefaces on Google Fonts.

If your favorite typeface isn’t published yet, [let us know](https://github.com/KyleAMathews/typefaces)
and we’ll add it!
