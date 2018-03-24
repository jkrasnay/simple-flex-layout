# Simple Flex Layout

This project is a study of simplified CSS classes to define an
application-like layout using flex properties.

The `vbox` and `hbox` classes trigger CSS flex properties to lay out the
element's children vertically or horizontally. By default, children
assume their default width and height. Adding the `fill` class causes
them to stretch to fill the missing vertical or horizontal space.

The `root` class triggers width and height to be 100%. Use on the
top-level of the layout.

The `pad` class triggers standard padding on its element. The `space`
class causes child elements to have standard spacing between them. `pad`
and `space` can be used on any element, but note the `space` by default
assumes vertical spacing (`margin-bottom`) unless it's also on a `hbox`
element.

The `scroll` class triggers `overflow:auto` so scroll bars will be shown
if the element's children exceeds the element's size.
