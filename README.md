### This is my personal version in german. Use it if it helps you.###

### Responsive Boilerplate for Style Tiles ###

Display your Style Tiles in beautiful, responsive way using valid HTML5/CSS3. This template is entirely and purposely based on the .PSD template provided by [Samantha Warren](https://twitter.com/SamanthaToy) at [StyleTil.es](http://styletil.es). If you don't know what a Style Tile is yet:

>Style Tiles are a design deliverable consisting of fonts, colors and interface elements that communicate the essence of a visual brand for the web.
>
>They help form a common visual language between the designers and the stakeholders and provide a catalyst for discussions around the preferences and goals of the client.
>
>Style Tiles are similar to the paint chips and fabric swatches an interior designer gets approval on before designing a room. An interior designer doesn't design three different rooms for a client at the first kick-off meeting, so why do Web designers design three different webpage mockups?

## How do I use it? ##

You'll need knowledge of basic HTML and CSS. Edit the text and logo in the HTML, but everything else is CSS.

If you'd like to have switchable tiles:

1. Add a separate stylesheet for each tile to the `css` folder.
1. Uncomment the scripts at the bottom of `index.html`.
1. Using the commented stylesheets links in the header as a reference, add your new stylesheets. Ensure the `title` attribute is included.
1. Under the `#project` div, follow the commented instructions: comment out (or delete) the text-only `<p>` element and uncomment the one below with links. Adapt as necessary, ensuring the `rel` attribute in the links match the `title` attribute in the stylesheet links.

*Note: The first linked stylesheet option in the `#project` div will be the default. If that's an issue, make the first option point to a blank stylesheet.*

## Credits ##

* Textures are from [Flickr](http://www.flickr.com/groups/freetextures)
* jQuery CSS switcher adapted from [Kelvin Luck's](http://www.kelvinluck.com/assets/jquery/styleswitch/toggle.html)

## Changelog ##

* 6/11/12 - Initial commit.
* 6/12/12 - Added tile switching functionality.
