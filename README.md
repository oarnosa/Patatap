# Patatap

> A sound and animation on key press project built on Paperscript and Howler.js

## Table of contents

- [General info](#general-info)
- [Technologies](#technologies)
- [Code examples](#code-examples)
- [Status](#status)
- [Inspiration](#inspiration)

## General info

The purpose of this project was to serve as an introduction to working with animations and sounds in javascript. For the animations, a library called Paper.js is utilized which is an open source vector graphics scripting framework which runs ontop of the HTML5 Canvas. This framework allows the animation of elements within a rendered space declared as a Canvas. Howler.js is an audio library which makes working with audio files easy by creating Howls for the audio files. Both of these libraries work seamlessly together to produce a sound and animation for different key presses.

This app is hosted via Heroku at https://oarnosa-patatap-clone.herokuapp.com

## Technologies

- Paper.js - version 0.12.3
- Howler.js - version 2.1.2
- jQuery - version 3.4.1

## Code examples

Example of the Paper.js script which expands on the HTML5 canvas element and creates an area to allow the animation of objects:

```html
<script type="text/paperscript" canvas="myCanvas"></script>
```

Example of a Howler.js Howl:

```javascript
var sound = new Howl({
  src: ["sound.mp3"]
});
sound.play();
```

## Status

Project is: _in progress_, as I would like to add more dynamic and varied effects to the animations.

## Inspiration

This project was inspired by the original [Patatap](patatap.com) which I highly recommend you check out!
