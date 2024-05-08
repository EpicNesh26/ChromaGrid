## ChromaGrid

### Overview of the Project: 
ChromaGrid is a simple grid layout that displays a series of cards with a hover effect. The layout is created using CSS Grid and has a 4x4 grid with each card having a width and height of 150px. The cards are positioned relatively and have a background color of rgba(45, 45, 45, 1). <br>
https://github.com/EpicNesh26/ChromaGrid/blob/c928b0ae6798e00647330eedd2d3e4fe9935578d/style.css#L16-L28

When the user hovers over a card, a radial gradient appears in the center of the card, creating a subtle animation effect. The gradient is created using the ::before pseudo-element and is positioned using the --x and --y custom properties. The gradient's opacity is set to 0 by default and transitions to 1 when the user hovers over the card. <br>

The card also has an ::after pseudo-element that creates a semi-transparent background, giving the card a subtle shadow effect.
<br>

Overall, this project is a great example of how to use CSS Grid and custom properties to create a dynamic and interactive layout. The hover effect adds a nice touch to the design and can be easily customized to fit different design needs.
