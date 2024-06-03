# Keybind Manager

Keybind Manager is a Garry's Mod addon that provides a convenient way to manage and customize keybinds. It allows players to create, edit, and delete keybinds, as well as organize them into different profiles.

## Features

- Create and manage multiple keybind profiles
- Bind keys to execute console commands or default actions
- Intuitive and user-friendly menu interface
- Customizable keybind names, descriptions, and commands
- Ability to save and load keybind profiles
- Support for default keybinds and custom keybinds
- Integration with the spawnmenu for quick access
- Profiles are stored as .json files in garrysmod/data/keybindmanager

## Installation

1. Download the latest version of Keybind Manager from this GitHub repository by either cloning or downloading the repo via zip.
2. Extract the downloaded files and place the `keybindmanager` folder into your Garry's Mod addons directory (`garrysmod/addons/`).
3. Restart your Garry's Mod to load the addon.

## Usage

1. Launch Garry's Mod and join a server or start a new game.
2. Open the Keybind Manager menu using one of the following methods:
   - Open the console and type in `open_keybind_manager`
   - Access the Keybind Manager through the spawnmenu under "Utilities" > "Keybind Manager".
3. Create a new profile or select an existing profile from the dropdown menu.
4. Add, edit, or delete keybinds using the provided options in the menu.
5. Customize the keybind name, description, command, and key for each keybind.
6. Save your changes and close the menu.
7. The keybinds will now be active and can be used in-game.

## Configuration

Keybind Manager does not require any additional configuration. However, you can customize the addon by modifying the following files:

- `lua/keybind_manager/core.lua`: Contains the core functionality of the addon, including keybind registration, saving, and loading.
- `lua/keybind_manager/menu.lua`: Defines the user interface and menu functionality for managing keybinds.
- `lua/keybind_manager/spawnmenu.lua`: Integrates the Keybind Manager with the spawnmenu for easy access.

## File Structure

Keybind Manager consists of the following files:

- `lua/autorun/keybind_manager.lua`: The main entry point of the addon, responsible for including the necessary files on both the server and client.
- `lua/keybind_manager/core.lua`: Contains the core functionality of the addon, including keybind registration, saving, and loading.
- `lua/keybind_manager/menu.lua`: Defines the user interface and menu functionality for managing keybinds.
- `lua/keybind_manager/spawnmenu.lua`: Integrates the Keybind Manager with the spawnmenu for easy access.

## Contributing

Contributions to Keybind Manager are welcome! If you encounter any issues, have suggestions for improvements, or would like to contribute new features, please feel free to submit a pull request.

## License

This addon is released under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). Please review the license terms before using or distributing the addon.