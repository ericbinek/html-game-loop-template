# HTML Game Template

This template provides a simple HTML framework for creating a grid-based game using a canvas element. The game loop is handled using `requestAnimationFrame` to ensure smooth animations.

## Features

- 16x16 grid with each cell being 16x16 pixels.
- Basic game loop setup with `requestAnimationFrame`.
- Simple rendering function to draw the grid on the canvas.

## Usage

1. Clone this repository or click on `Use this template` to create a new repository based on this template.
2. Open the `index.html` file in your browser to see the grid.
3. Start building your game by updating the `update` and `render` functions in the `script` tag within `index.html`.
   - The `update` function is where you will update your game state.
   - The `render` function is where you will draw your game state to the canvas.

## Customization

- Change the grid size and cell size by updating the `gridRows`, `gridColumns`, and `cellSize` constants.
- Add your game logic in the `update` function.
- Draw your game state in the `render` function.
- Add your CSS styles within the `style` tag in the `head` section of `index.html`.

## Contributing

Feel free to fork this repository and make changes, or open issues and pull requests if you have suggestions to improve this template.

## License

This project is open source and available under the [The Unlicense](LICENSE).
