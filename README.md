# SVG and Clip-Path Backrounds

I want to learn how to make transitions between different sections of a landing page. See the following images for examples:

I also wanted to learn gradients while I was at it.

## Backgrounds

There are two ways to make a custom backgournd:

1. Using SVGs
2. Using the css property `clip-path`

### Using SVGs as Backgrounds

- Is is very easy to make custom section dividers with SVGs:: just go to [shapedivider.app](https://www.shapedivider.app/).
- After crafting your desired section copy and paste the html & css. Make sure the parent contianer of the SVG div has the css property: `position: relative`.
  - If you don't, your dividers will float to the top.

#### Pros:

- Allows for more dynamic/complex shapes inbetween wewbpage sections

#### Cons:

- SVGs are not easy to use with gradients. They can only cut out one color
  - Because of This you must always cut out of a gradient color if you're using one
- Some contents may be covered by the svg - They will have to be moved around
  -Messier Code (Can be be modularized with React Frameworks)

### Using `clip-path` as a Background

- Cleaner code
- Really only allows for the slanted line design
- Some contents may be covered by the clip-path - They will have to be moved around

## Technologies Used

1. [Normalize.css](https://github.com/necolas/normalize.css/)
2. [shapedivider.app](https://www.shapedivider.app/)
   1. [getwaves.io](https://getwaves.io/) (Simpler Alternative)
3. [Clippy CSS Clip-Path Generator](https://bennettfeely.com/clippy/)
