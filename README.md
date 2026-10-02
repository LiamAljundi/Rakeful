# Rakeful

A digital Zen garden. Drag across a field of sand to rake patterns into it, pick a rake
with 3, 4 or 5 teeth, and reset to smooth the sand again.

- **Try it:** [liamaljundi.github.io/Rakeful](https://liamaljundi.github.io/Rakeful/)
- **More of my work:** [liamaljundi.com](https://www.liamaljundi.com)

A group project from my first programming course during my Interaction Design studies
(2019), made with plain HTML, CSS and JavaScript on a canvas, with no libraries.

## How it works

- **The sand** is a grid of particles on a canvas. They're laid out with a loop inside a
  loop, the same trick as the chessboard exercise in *Eloquent JavaScript*, starting from
  the particles tutorial in class and the
  [30,000 particles](https://codepen.io/soulwire/pen/Ffvlo) demo by soulwire.
- **The rake** is an array of tooth positions that follows the mouse. While you drag,
  particles under each tooth are pushed to its sides, leaving a groove.
- **The controls** reset the sand and switch between a 3, 4 or 5-tooth rake.

## Run it locally

Open `index.html` in a browser. There's no build step and nothing to install.
