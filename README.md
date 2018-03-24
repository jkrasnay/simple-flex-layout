# Simple Flex Layout

This project is a study of simplified CSS classes to define an
application-like layout using flex properties.

The `vbox` and `hbox` classes trigger CSS flex properties to lay out the
element's children vertically or horizontally. By default, children
assume their default width and height. Adding the `stretch` class causes
them to stretch to fill the missing vertical or horizontal space.

The `root` class triggers width and height to be 100%. Use on the
top-level of the layout.

The `padded` class triggers standard padding on its element. The
`spaced` class causes child elements to have standard spacing between
them. `padded` and `spaced` can be used on any element, but note the
`spaced` by default assumes vertical spacing (`margin-bottom`) unless
it's also on a `hbox` element.

The `scrollable` class triggers `overflow:auto` so scroll bars will be
shown if the element's children exceeds the element's size.
