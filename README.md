# London-Skyline

A simple animated webpage of the London Skyline. For the purpose of learning illustration graphics and animations.

### Steps:

- [x] Create SVG using Illustration software
- [x] Simple Create-React-App
- [x] Decide on implementation for SVG (e.g. Inline SVG, HTML Object, PNG Image)
  - HTML object was the obvious choice for an SVG of this size. The image below provides a rounded list of the benefits of each.
- [x] Decide on animation type (e.g. CSS, SMIL, JS, CSS/JS Library)
  - Given our SVG was an object. CSS was the most appropriate
  - A library seemed unnecessary for what we had planned
- [x] Animate clouds
  - This involved a rather simple implementation of `transform: translateX()` on an infinite loop
- [x] Animate Lights, Shadow and Background
  - These were done by manipulating the `opacity` of the elements, back and forth in a Day/Night cycle
- [ ] Animate Clock Hands
  - I detailed a few short attempts at this, but the total project time, work commitment and other planned projects encouraged moving quickly forward. I am certain the solution is simple; but balance of time takes precedence.
- [x] Refactor code
  - This was done at each step.

<p align="center">
    <img src="https://miro.medium.com/max/875/1*YRtXfVLMzsUra4c8MVtQOQ.png" alt="https://medium.com/better-programming/react-best-way-of-importing-svg-the-how-and-why-f7c968272dd9" height=200>
</p>

### Useful Illustrator Functions:

I recommend following the 'Illustrator Get Started course' found [here](https://helpx.adobe.com/illustrator/tutorials.html)

- Pattern Fill: Responsible for the railings and bricks of Tower Bridge
- Shape Builder Tool/Compound Paths: Great tools for joining shapes together
- Scatter Brush + Curvature Tool: Used to easily create the randomised spread of leaves on the trees from a single path and leaf shape
- Clipping Mask: Masks an artwork so it's only visible in the shape of the object. Used to curve the British Flag on the Tower of London.
- Gradients: Used to create the gold colours, glow of the sun/moon, Big Ben spotlight, etc.
- Drop Shadows: The core attribute of 3D art. Adding shadow brings realism to the art
- Outer glow: Creates the effect of the light coming from a source (e.g. windows)

### Useful Tools:

- [Create React App](https://create-react-app.dev/) for quick, simple web app
- [Adobe Illustrator](https://www.adobe.com/uk/products/illustrator.html) - £££ SVG Editor
- [SVGOMG](https://jakearchibald.github.io/svgomg/) for optimising SVGs
- [Excalidraw](https://excalidraw.com/) - Free Virtual Whiteboard/SVG Editor
- [svg2jsx](https://svg2jsx.com/) for converting SVGs to jsx compatible format (size limit)
- [Vectr](https://vectr.com/)- Free SVG Editor

### Animation Libraries:

- https://snapsvg.io/docs/
- https://github.com/animate-css/animate.css
- https://github.com/joerez/woah.css
- https://github.com/yesiamrocks/cssanimation.io

### Inspiration:

- https://codepen.io/marijoha/full/xRgqKG/
- https://images.vexels.com/media/users/3/78755/raw/b04c23d75fba18d9d4001b0ed2718f00-london-city-skyline.jpg
- https://free-images.com/or/c456/london_skyline_svg.jpg
- https://tse1.mm.bing.net/th?id=OIP.yaC6jKI9ei3QJH8E6RzzkwHaE7&pid=Api
