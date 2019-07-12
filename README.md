Easy example on how to put marker on a d3.js map.

You got 2 options:
- using d3.geo.path() which does all the work for you
- using svg circles and translating them via projection(d.geometry.coordinates)