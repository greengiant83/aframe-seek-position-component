## aframe-seek-position-component

[![Version](http://img.shields.io/npm/v/aframe-seek-position-component.svg?style=flat-square)](https://npmjs.org/package/aframe-seek-position-component)
[![License](http://img.shields.io/npm/l/aframe-seek-position-component.svg?style=flat-square)](https://npmjs.org/package/aframe-seek-position-component)

Animates elements to a target position. It uses linear interpolation to "ease" the element to its target position. It is smart enough to stop calculating animations once the element has reached its target. Target positions can be updated at any time and the element will start heading for its new destination. To use

For [A-Frame](https://aframe.io).

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.6.0/aframe.min.js"></script>
  <script src="https://unpkg.com/aframe-seek-position-component/dist/aframe-seek-position-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity seek-position="0 1 34"></a-entity><!-- seek-position takes a vector3 world position as input -->
  </a-scene>
</body>
```

<!-- If component is accepted to the Registry, uncomment this. -->
<!--
Or with [angle](https://npmjs.com/package/angle/), you can install the proper
version of the component straight into your HTML file, respective to your
version of A-Frame:

```sh
angle install aframe-seek-position-component
```
-->

#### npm

Install via npm:

```bash
npm install aframe-seek-position-component
```

Then require and use.

```js
require('aframe');
require('aframe-seek-position-component');
```
