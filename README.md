# Stencil Rating Scale

Create a configurable [likert scale](http://en.wikipedia.org/wiki/Likert_scale).
Thanks to Mike Lee and [Hugo Giraudel](http://hugogiraudel.com/2014/02/24/star-rating-system-with-sass/)!

[Link to demo](#)

## Requirements

- Sass
- AMD loader
- Dust templating

## Installation

Note: I've modified Gruntfile.js slightly so that the icons will be displayed. This needs to be fixed and is also noted below.

## Usage

- Edit the `data-rating` attribute belonging to `.c-scale` to change scale rating
- Make sure the # of `.c-scale__items` matches `$rating-scale__count` in the scss

## Development

- run npm install
- run bower install
- run grunt serve
- navigate to localhost:3000/tests/visual

## Todos

- Move template from HTML file to dust file
- Setup extend for star increments
- Need proper setup for gruntfile when working with assets


