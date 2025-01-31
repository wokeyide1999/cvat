---
title: 'Settings'
linkTitle: 'Settings'
weight: 13
---
To open the settings open the user menu in the header and select the settings item or press `F2`.

![](/images/image067.jpg)

`Settings` have two tabs:

In tab `Player` you can:

- Control step of `C` and `V` shortcuts.
- Control speed of `Space`/`Play` button.
- Select canvas background color. You can choose a background color or enter manually (in RGB or HEX format).
- `Reset zoom` Show every image in full size or zoomed out like previous
  (it is enabled by default for interpolation mode and disabled for annotation mode).
- `Rotate all images` checkbox — switch the rotation of all frames or an individual frame.
- `Smooth image` checkbox — smooth image when zoom-in it.

  |        _smoothed_         |        _pixelized_         |
  |---------------------------|----------------------------|
  | ![](/images/smoothed.jpg) | ![](/images/pixelized.jpg) |

---

In tab `Workspace` you can:

![](/images/image155.jpg)

- `Enable auto save` checkbox — turned off by default.
- `Auto save interval (min)` input box — 15 minutes by default.
- `Show all interpolation tracks` checkbox — shows hidden objects on the
  side panel for every interpolated object (turned off by default).
- `Always show object details` - show text for an object on the canvas not only when the object is activated:

  ![](/images/image152_detrac.jpg)

- `Position of a text` - text positioning mode selection:
  - `Auto` - the object details will be automatically placed where free space is.
  - `Center` - the object details will be embedded to a corresponding object if possible.

- `Font size of a text` - specifies the text size of the object details.

- `Automatic bordering` - enable automatic bordering for polygons and polylines during drawing/editing.
  For more information To find out more, go to the section [annotation with polygons](/docs/manual/advanced/annotation-with-polygons/).

- `Intelligent polygon cropping` - activates intelligent cropping when editing the polygon (read more in the section [edit polygon](/docs/manual/advanced/annotation-with-polygons/edit-polygon/)

- `Attribute annotation mode (AAM) zoom margin` input box — defines margins (in px)
  for shape in the attribute annotation mode.
- Click `Save` to save settings (settings will be saved on the server and will not change after the page is refreshed).
  Click `Cancel` or press `F2` to return to the annotation.

- `Default number of points in polygon approximation`
  With this setting, you can choose the default number of points in polygon.
  Works for serverless interactors and OpenCV scissors.
