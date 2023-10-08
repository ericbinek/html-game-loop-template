# HTML Game Template

This template provides a basic framework for creating a grid-based game using an HTML canvas element. It includes a game loop handled via `requestAnimationFrame` to ensure smooth animations.

## Features

- 16x16 grid with each cell being 16x16 pixels.
- Basic game loop setup with `requestAnimationFrame`.
- Simple rendering function to draw the grid on the canvas.
- Start and Stop feature to control the game loop.
- Tick counter to track the game progress.
- Dynamic FPS (Frames Per Second) adjustment feature for testing under different frame rates or adjusting game speed.

## Usage

1. Clone this repository or click on "Use this template" to create a new repository based on this template.
2. Open the `index.html` file in your browser to see the grid.
3. Start building your game by updating the `update` and `render` functions in the script tag within `index.html`.
   - The `update` function is where you will update your game state.
   - The `render` function is where you will draw your game state to the canvas.

## Customization

- Change the grid size and cell size by updating the `gridRows`, `gridColumns`, and `cellSize` constants.
- Add your game logic in the `update` function.
- Draw your game state in the `render` function.
- Add your CSS styles within the style tag in the head section of `index.html`.
- Utilize the Start and Stop buttons to control the game loop.
- Use the Increase FPS and Decrease FPS buttons to dynamically adjust the game's frame rate.

## FPS Management

- The FPS rate can be increased or decreased by steps of 10, within a range of 10 to 60 FPS, using the Increase FPS and Decrease FPS buttons.
- The current FPS rate is displayed to the user for feedback.
- Changes to the FPS rate are reflected immediately in the game loop's frame duration, affecting the game speed accordingly.

## Contributing

Feel free to fork this repository and make changes, or open issues and pull requests if you have suggestions to improve this template.

## License

This project is open source and available under the [The Unlicense](LICENSE).
