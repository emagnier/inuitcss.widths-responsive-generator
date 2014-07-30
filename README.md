# Widths-responsive Generator

The inuitcss `widths-responsive-generator` module is an extension of the [`widths-generator`
module](https://github.com/emagnier/inuitcss.widths-generator).

This module **completely replace the default [`widths-responsive`](https://github.com/inuitcss/trumps.widths-responsive)
module** of inuitcss. So it's not necessary to load both the default `widths-responsive` module
and the `widths-responsive-generator` module.


## Installation

Install using Bower:

    $ bower install --save inuit-widths-responsive-generator


## Configuration

`widths-responsive-generator` will inherit the same settings used for [`widths-generator`](https://github.com/emagnier/inuitcss.widths-generator) (i.e.
namespaces and fraction vs. spoken-word format).

`widths-responsive-generator` loops through the breakpoints defined in
[`settings.responsive`](https://github.com/inuitcss/settings.responsive) to generate prefixed breakpoint-based classes. If you are
using inuitcss’ default breakpoints, you will be given classes like
`lap-and-up-1/4`, or `desk-one-half`, etc.


## Licence

[MIT](http://opensource.org/licenses/MIT) © Etienne Magnier
