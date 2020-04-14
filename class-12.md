# External Article
## _Easily Create Stunning Animated Charts with Chart.js_
- **Chart.js** is a JavaScript plugin that utilizes the canvas element within HTML5 to draw graphs on pages, and can create _bar_, _line_, and _pie_ charts.
- Its supposedly simple and easy to use, as well as quite flexible.

## _Basic Usage of Canvas_
- The `<canvas>` element has only two attributes, `width` and `height`, which are also optional and can be set using DOM properties.  Canvas dimensions are defaulted to 300px x 150px when no `width` and `height` attributes are specified.
- Unlike an `<image>` tag, the `<canvas>` element makes it easy to define fallback content.
- The `<canvas>` element creates a fixed-size drawing surface which exposes one or more **rendering contexts** which are utilized to create and manipulate shown content.

## _Drawing Shapes with Canvas_
- `<canvas>` supports only the two primitive shapes of rectangle and path.
- The three functions that draw rectangles are:
    - `fillRect(x, y, width, height)`
    - `strokeRect(x, y, width, height)`
    - `clearRect(x, y, width, height)`
- The methods used to draw paths are:
    - `beginPath()`
    - `closePath()`
    - `stroke()`
    - `fill()`
- The `moveTo(x, y)` function moves the pen and the `lineTo(x, y)` method draws a line to the specified `x` and `y` coordinates.
- The `arc()` and `arcTo()` methods draw arcs or circles.
- Curves are drawn with `quadraticCurveTo(cp1x, cp1y, x, y)` and `bezierCurveTo(cp1x, cp1y, x, y)`.

## _Applying Styles and Colors_
- `fillStyle` and `strokeStyle` are used to apply colors to shapes.
- Translucent shapes are drawn by either setting the `globalAlpha` property or by assigning a semi-transparent color to the stroke and/or fill style.
- Shapes can be filled and stroked using linear and radial gradients.
- A series of loops can be used to create patterns of images.
- Applying shadows involves the four properies `shadowOffsetX`, `shadowOffsetY`, `shadowBlur`, and `shadowColor`.

## _Drawing Text_
- The two methods to render text are `fillText(text, x, y [, maxWidth])` and `strokeText(text, x, y [maxWidth])`.
- Properties which adjust how text gets displayed on the canvas are `font`, `textAlign`, `textBaseline`, and `direction`.