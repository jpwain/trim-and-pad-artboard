## Trim & Pad Artboard

Resize [Sketch](http://bohemiancoding.com/sketch) artboards to fit content, with padding around all sides.

### Usage

Select one or more artboards and press <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>z</kbd>.

This command is also accessible in the Plugins menu:

    Plugins → Trim & Pad Artboard

### Customize padding

To adjust the padding value, edit the `padding` value on the first line of the [shared.js](/trim_and_pad_artboard.sketchplugin/contents/sketch/shared.js) file.

### Features

- When resizing an artboard to fit content, only visible layers are considered, but the relative positioning of hidden layers with respect to visible layers is preserved.
- Select multiple artboards to resize many at once.
- Select a layer to resize the parent artboard. Also works for multiple parent artboards when selecting multiple layers across artboards.

### License & info

Version 1.0

[MIT License](https://opensource.org/licenses/MIT)

Forked from [Resize Artboard](https://github.com/zhifengkoh/resize_artboard)

### Changelog

#### Version 1.0

- Forked, adjusted, cleaned up, published.