Juiced Up Layouts
-----------------

A set of 8 splash page flexbox based layouts for Backdrop CMS.

Backdrop CMS allows you to easily specify layouts (design skeletons/wireframes) for a URL on your site (or set of paths to pages).
One use-case you may have for your website is a splash page, full screen page, single page marketing website, or "big sell" page.
These set of layouts seek to provide this.  These layouts are not for text rich, content heavy pages.

These set of layouts provide/rely on a lightweight CSS flexbox grid system called JuicedCSS by Joey Lea ( http://juicedcss.com ).
You may read about using this layout system here: http://juicedcss.com/bower_components/juiced/docs/layout.html .
If you are using this layout, you may use these grid classes in your theme's CSS -- .col-3 .col-order-1 etc...

One of the goals of these layouts is to be as semantic HTML and accessible as possible in 2016.

These layouts are not for every demographic since they rely on CSS Flexbox -- a newer technology.  Check out which browsers support Flexbox at http://caniuse.com/#search=flexbox .

These layouts over-ride your theme's CSS for they pages they are enabled on.  Their purpose is to provide an out-of-the-box splash page for your site.

These layouts are in a beta stage and are being tested and molded to work with every Backdrop theme as of 3/2016.

The layouts contained within this set are:

juiced_up_full_screen_top -- a full screen content area with the site menu at the top
juiced_up_full_screen_bottom -- a full screen content area with the site menu at the bottom
juiced_up_full_screen_left -- a full screen content area with the site menu at the left
juiced_up_full_screen_right -- a full screen content area with the site menu at the right
juiced_up_full_screen_none -- a full screen content area with the site menu below the fold
juiced_up_split_screen  -- a full screen, split screen content area with the site menu at the top
juiced_up_split_screen_none  -- a full screen, split screen content area with the site menu below the fold
juiced_up_startup66 -- a full screen 66% screen content area with common regions tech startup websites often use.
juiced_up_demo -- the layout used on the demo website http://dev-backdropthemes.pantheon.io/node/36

These layouts provide certain regions that supportive themes can use to add background images to from the UI.  One reason you might use this is for a site administrator (not the original development team) to easily add different background images to the full screen splash page whenever they want.

JuicedCSS is under the MIT license.  Special thanks to Joey Lea for this grid system!

These layouts currently (temporarily) use thumbnails from Radix layouts while we develop thumbnails especially for this set.  Credits go to @arshad for them.

## Features

* Responsive out of the box
* Works with most Backdrop themes.
* Easily extendable to support new layouts and new regions.

## Installation

1. Download or clone this repository.
2. Extract to */layouts* such that this README.md file is at layouts/juiced_up_layouts/README.md

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

## Current Maintainers

* biolithic(http://github.com/biolithic)
-- contributors/maintainers are definitely welcome!!!!
