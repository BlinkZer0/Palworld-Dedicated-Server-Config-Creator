# Palworld Dedicated Server Config Creator

A single-file HTML tool for creating and editing Palworld dedicated server configuration files (PalWorldSettings.ini). This tool simplifies the configuration process by providing an intuitive web interface for managing the hundreds of server parameters.

## Preview

[📄 **View Full Documentation PDF** - Palworld Server Settings Editor.pdf](Palworld%20Server%20Settings%20Editor.pdf)

> **Note:** GitHub doesn't support embedded PDF iframes, but you can click the link above to view the full documentation demonstrating the tool's functionality.

## Features

- **User-Friendly Interface**: Clean, organized sections for different configuration categories
- **Load Existing Configs**: Import and edit existing `.ini` files
- **Export Configuration**: Generate properly formatted `PalWorldSettings.ini` content
- **Copy to Clipboard**: Quickly copy generated configuration
- **Reset to Defaults**: Restore all settings to default values
- **Tooltips**: Helpful information for each setting
- **Responsive Design**: Works on desktop and mobile devices
- **No Installation Required**: Single HTML file with no dependencies

## Configuration Sections

- **Server Information**: Server name, description, passwords, ports, and region
- **Multiplayer Settings**: Player limits, PvP, guilds, and crossplay options
- **Gameplay Settings**: Difficulty, experience rates, death penalties, and time settings
- **Randomizer Settings**: World randomization options
- **Player Settings**: Damage, hunger, stamina, and HP regeneration rates
- **Pal Settings**: Spawn rates, stats, egg hatching, and Palbox options
- **Base & Building Settings**: Build limits, worker counts, and deterioration rates
- **Drops & Resources**: Collection rates, respawn speeds, and drop settings
- **Guild & Auto-Reset Settings**: Guild management and auto-reset timers
- **Enemy & Invader Settings**: Enemy invasion controls
- **Server Management**: Auto-save, chat limits, backup settings
- **RCON & REST API**: Remote console and API configuration

## Usage

1. Open `PalWorldSettingsEditor.html` in any modern web browser
2. Configure your server settings using the form fields
3. Click **"Generate INI Output"** to create the configuration
4. Click **"Copy to Clipboard"** to copy the generated content
5. Paste the content into your `PalWorldSettings.ini` file located at:
   - Windows: `<YourPalServerFolder>\Pal\Saved\Config\WindowsServer\PalWorldSettings.ini`
   - Linux: `<YourPalServerFolder>/Pal/Saved/Config/LinuxServer/PalWorldSettings.ini`

### Loading Existing Configuration

1. Click **"Load from INI File"**
2. Select your existing `PalWorldSettings.ini` file
3. All fields will be populated with your current settings
4. Make changes and regenerate the configuration

## File Structure

This is a standalone project consisting of a single HTML file:
- `PalWorldSettingsEditor.html` - Complete web application with embedded CSS and JavaScript

## Browser Compatibility

Works with all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## Why Use This Tool?

Palworld's server configuration file uses a monolithic single-line format with hundreds of parameters, making it extremely difficult to edit manually. This tool:

- Organizes settings into logical categories
- Provides validation for numeric ranges
- Includes descriptions for each parameter
- Prevents formatting errors
- Saves time and reduces configuration mistakes

## Contributing

This is a single-file project. To contribute:
1. Fork the repository
2. Make changes to `PalWorldSettingsEditor.html`
3. Test thoroughly in multiple browsers
4. Submit a pull request

## License

This project is provided as-is for the Palworld community.

## Disclaimer

This is an unofficial tool and is not affiliated with Pocketpair or Palworld. Always backup your server configuration before making changes.
