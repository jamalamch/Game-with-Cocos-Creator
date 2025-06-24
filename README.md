# Game-with-Cocos-Creator

A Scrabble-like word game built using [Cocos Creator](https://www.cocos.com/en/creator). This project demonstrates the use of Cocos Creator's scene editor, scripting, and asset management to create a fun and interactive board game experience.

## Features

- Classic gameplay with customizable rules
- Drag-and-drop tile placement
- Score calculation and validation
- Multiple scenes for menu, gameplay, and results
- Responsive UI and animations
- Localization support (i18n)
- Modular asset structure for easy expansion
- Multiplayer support (local and/or online, depending on configuration)
- Save/load game state
- Sound effects and background music
- Hint and shuffle features

## Project Structure

- `assets/`: Game assets including images, prefabs, scenes, and scripts
- `extensions/`: Editor and engine extensions, including type definitions
- `server/`: Backend server code (if applicable)
- `settings/`: Project and builder configuration files
- `licenses/`: License agreements and copyright

## Getting Started

1. **Install [Cocos Creator](https://www.cocos.com/en/creator) (v3.x recommended).**
2. **Clone this repository:**
    ```sh
    git clone <repo-url>
    ```
3. **Open the project in Cocos Creator.**
4. **Install dependencies (if using the server):**
    ```sh
    cd server
    npm install
    ```
5. **Run the game:**  
    Use the Cocos Creator editor to preview and play the game.
6. **For server features, run:**
    ```sh
    npm start
    ```

## Gameplay Overview

- Players take turns forming words on the board using letter tiles.
- Each tile has a point value; special board squares provide bonuses.
- The game ends when all tiles are used or no more moves are possible.
- The player with the highest score wins.

## Customization

- **Rules:** Easily modify tile distribution, board layout, and scoring in the configuration files.
- **Assets:** Swap out images, sounds, and UI elements in the `assets/` folder.
- **Localization:** Add new languages by updating the i18n files.

## Localization

The project supports multiple languages using well-defined i18n keys (see `extensions/pipeline/@types/packages/engine-extends/@types/i18n-well-defined.d.ts`).

## Contributing

Contributions are welcome! Please open issues or submit pull requests for bug fixes, new features, or improvements.

## License

See `licenses/Cocos Cyberpunnk Content License Agreement.md` for content usage terms.

> Not affiliated with Scrabble® or its trademark owners.

## Credits

Built with Cocos Creator  
Assets and code © Xiamen Yaji Software Co., Ltd. and contributors