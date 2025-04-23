# SVG

- SVG stands for Scalable Vector Graphics.
- SVG defines vector-based graphics in XML format.
- SVG graphics are scalable, and do not lose any quality if they are zoomed or resized.

## My First SVG

```svg
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>
```

<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>

## SVG is a W3C Recommendation

SVG 1.0 became a W3C Recommendation on 4 September 2001.

SVG 1.1 became a W3C Recommendation on 14 January 2003.

SVG 1.1 (Second Edition) became a W3C Recommendation on 16 August 2011.

## SVG Advantages

Advantages of using SVG over other image formats (like JPEG and GIF) are:

- SVG images can be created and edited with any text editor
- SVG images can be searched, indexed, scripted, and compressed
- SVG images are scalable
- SVG images can be printed with high quality at any resolution
- SVG images are zoomable
- SVG graphics do NOT lose any quality if they are zoomed or resized
- SVG is an open standard
- SVG files are pure XML

## How does it work?

SVG has elements and attributes for rectangles, circles, ellipses, lines, polygons, curves, and more.

SVG also supports filter and blur effects, gradients, rotations, animations, interactivity with JavaScript, and more.

A simple SVG document consists of the `<svg>` root element and several basic shape elements that will build a graphic together.

<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
  <text fill="black" x="50" y="50" text-anchor="middle" dominant-baseline="middle" font-family="sans-serif" font-size="12">Hello World</text>
</svg>

## SVG Shapes

SVG has some predefined shape elements that can be used by developers:

Rectangle `<rect>`
Circle `<circle>`
Ellipse `<ellipse>`
Line `<line>`
Polyline `<polyline>`
Polygon `<polygon>`
Path `<path>`
