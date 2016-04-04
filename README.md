# Typescript Test
#### Requirements
  - ExtendScript processes `/src/creative/test.psd` with **Photoshop CC**
  - Pull out each layer of the .psd and export it as a png to `/build/images`
  - Each image should be a different size, since all layers are rectangles, no transparency should be included in the .png's after processing.
  - Name each .png as the layer name.
  - Generate an `atlas.json` that contains an collection of objects that describe the image in the PSD in terms of the `name`, `x`,`y` pos and `width` and `height` and place it in `/build`.
  - Have the job run on a grunt task
  - Build your solution in a separate branch.
  - Submit your solution as a Pull Request.

#### Example
```
[
  {
    "name": "spin-button",
    x: 1,
    y: 100,
    width: 200,
    height: 400
  }
]
```
