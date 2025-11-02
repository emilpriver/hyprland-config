# Hyprland Configuration

A comprehensive Hyprland window manager configuration with advanced features, custom scripts, and extensive customization options.

Based on [JaKooLit's Arch-Hyprland](https://github.com/JaKooLit/Arch-Hyprland) starter kit with custom modifications and personal tweaks.

## Installation

This configuration is installed in `~/.config/hypr/`

## Project Structure

### Core Configuration Files
- `hyprland.conf` - Main Hyprland configuration file
- `monitors.conf` - Monitor configuration and setup
- `workspaces.conf` - Workspace rules and configuration
- `application-style.conf` - Application-specific styling
- `hypridle.conf` - Idle management configuration
- `hyprlock.conf` / `hyprlock-1080p.conf` - Lock screen configurations

### Directories

#### `animations/`
Multiple animation profiles for different preferences:
- Default configurations
- HYDE profiles (default, minimal, optimized, vertical)
- ML4W profiles (classic, dynamic, fast, high, moving, standard)
- Custom profiles by Mahaveer
- Option to disable animations

#### `configs/`
- `Keybinds.conf` - Keyboard shortcuts and bindings

#### `scripts/`
Extensive collection of utility scripts:
- **System Management**: `AirplaneMode.sh`, `Battery.sh`, `GameMode.sh`, `Hypridle.sh`
- **Display**: `Brightness.sh`, `BrightnessKbd.sh`, `MonitorProfiles.sh`
- **Appearance**: `Animations.sh`, `ChangeBlur.sh`, `DarkLight.sh`, `Kitty_themes.sh`
- **Waybar**: `WaybarCava.sh`, `WaybarLayout.sh`, `WaybarScripts.sh`, `WaybarStyles.sh`
- **Utilities**: `ClipManager.sh`, `RofiEmoji.sh`, `ScreenShot.sh`, `Volume.sh`
- **Wallpaper**: `WallustSwww.sh`, `sddm_wallpaper.sh`
- **Window Management**: `KillActiveProcess.sh`, `Tak0-Autodispatch.sh`
- And many more...

#### `UserConfigs/`
User-customizable configuration files:
- `UserSettings.conf` - Personal settings
- `UserKeybinds.conf` - Custom keybindings
- `UserAnimations.conf` - Custom animation settings
- `UserDecorations.conf` - Window decoration settings
- `ENVariables.conf` - Environment variables
- `Startup_Apps.conf` - Applications to launch on startup
- `WindowRules.conf` - Window-specific rules
- `WorkSpaceRules` - Workspace-specific rules
- `LaptopDisplay.conf` / `Laptops.conf` - Laptop-specific configurations

#### `UserScripts/`
User-customizable scripts:
- `WallpaperAutoChange.sh` / `WallpaperRandom.sh` / `WallpaperSelect.sh` - Wallpaper management
- `WallpaperEffects.sh` - Wallpaper effects
- `RofiBeats.sh` / `RofiCalc.sh` - Rofi utilities
- `Weather.py` / `Weather.sh` - Weather information
- `ZshChangeTheme.sh` - Zsh theme management
- And more...

#### `Monitor_Profiles/`
Pre-configured monitor profiles for different setups

#### `wallpaper_effects/`
Wallpaper management and effects:
- `.wallpaper_current` - Current wallpaper reference
- `.wallpaper_modified` - Modified wallpaper reference

#### `wallust/`
Wallust integration for dynamic theming:
- `wallust-hyprland.conf` - Wallust configuration for Hyprland

## Features

- **Flexible Animation System**: Multiple animation profiles to choose from
- **Extensive Script Library**: Automation and utilities for common tasks
- **Customizable**: Separated user configs for easy personalization
- **Monitor Management**: Profile-based monitor configuration
- **Wallpaper Integration**: Dynamic wallpaper management with effects
- **Waybar Integration**: Custom scripts and layouts for Waybar
- **Gaming Support**: GameMode integration
- **Power Management**: Battery monitoring and idle management
- **Screen Lock**: Hyprlock integration with multiple resolution support

## Getting Started

1. Configuration files are located in `~/.config/hypr/`
2. Customize your settings in the `UserConfigs/` directory
3. Add your custom scripts to `UserScripts/`
4. Select your preferred animation profile from `animations/`
5. Configure your monitors in `monitors.conf` or use profiles from `Monitor_Profiles/`

