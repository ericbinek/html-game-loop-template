# HTML Game with 2D-Grid

This game template provides a foundation for creating a grid-based game using an HTML canvas element. It features a game loop managed by `requestAnimationFrame` to ensure smooth animations and also offers a statistics display for tracking game metrics.

## Features

- **16x16 Grid**: Each cell within this grid measures 16x16 pixels.
- **Game Loop**: Utilizes `requestAnimationFrame` for consistent animation frames.
- **Game Mechanics**:
  - Random grid cell selection and updating in each game iteration.
  - Tracking and displaying the load value for each grid cell.
  - Capturing statistics such as visit counts and resets for each cell.
- **Game State Management**:
  - Save Game State: Button to save the current game state, including the grid configuration and game statistics.
  - Load Game State: Button to load a previously saved game state, restoring the game's progression.
- **FPS Management**: 
  - Dynamic FPS (Frames Per Second) adjustment with buttons for both increasing and decreasing the rate.
  - Current FPS display for real-time feedback.
- **Game Control**:
  - Start and Stop buttons to initiate or halt the game loop.
  - Tick counter to provide insights into the game's progression.
- **Statistics Display**: 
  - A separate canvas for visualizing game metrics.
  - Toggle button to show or hide the statistics.

## Usage

1. Clone this repository.
2. Open the `index.html` file in your preferred browser to view the game grid.
3. Begin your game development by refining the `update` and `render` functions located within the `<script>` tag in `index.html`.
   - Use the `update` function to modify the game state.
   - Utilize the `render` function to illustrate the game state on the canvas.

## Customization

- Modify the grid dimensions and cell size by adjusting the `gridRows`, `gridColumns`, and `cellSize` constants.
- Integrate your game logic within the `update` function.
- Portray your game state in the `render` function.
- Embed your preferred CSS styling inside the `<style>` tag in the `<head>` section of `index.html`.
- Employ the Start, Stop, Increase FPS, Decrease FPS, and Show Stats buttons to interact with the game and its settings.

## Contributing

For those interested in enhancing this template, you're welcome to fork the repository and make modifications. If you have any suggestions or improvements, please open issues or submit pull requests.

## License

This project is open-source and freely available under the [The Unlicense](LICENSE).
