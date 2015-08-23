# ASP.NET 5 Bootstrap 4 (alpha)

The ASP.NET 5 web templates from @omnisharp/generator-aspnet updated for Bootstrap 4.

For ASP.NET 5 tooling team and for related projects.

## Web Application Basic

Take aways:
* update `Bower.json` dependency
* update `_Layout.cshtml` `link` and `script` tag helpers sources. Note that at moment the Microsoft Ajax CND does not support Bootstrap 4 yet - while Bootstrap CDN service does
* remove `Bootstrap Touch Carousel` together with `Hammer.js` dependencies - as `Bootstrap Touch Carousel` is no longer actively developed and maintained
* update `navbar` component structure as per BS4
* update `carousel` component structure as per BS4
* consistent use of `btn-primary` for primary action on forms
* use `card` components for ASP.NET 5 key concepts display [WIP]

![Web Application Basic](assets/20150822103303.jpg)

## Web Application

This is still WIP

Take aways:
* update `Bower.json` dependency
* update `_Layout.cshtml` `link` and `script` tag helpers sources. Note that at moment the Microsoft Ajax CND does not support Bootstrap 4 yet - while Bootstrap CDN service does
* remove `Bootstrap Touch Carousel` together with `Hammer.js` dependencies - as `Bootstrap Touch Carousel` is no longer actively developed and maintained
* update `navbar` component structure as per BS4
* update `carousel` component structure as per BS4
* update `form` tag helper: no `form-horizontal` required
* update `form-group`: add `row` class as there is no mixin for `form-group` now


## Author

@blazejewicz
