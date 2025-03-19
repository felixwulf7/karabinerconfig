# Karabiner Configuration Backup

This repository contains a backup of Karabiner-Elements configuration files from my personal setup.

## Version Information
- **Karabiner-Elements Version**: 13.7.0
- **Last Backup Date**: March 19, 2025
- **macOS Version**: Catalina 10.15.7

## Directory Structure
The configuration files are stored in their original directory structure:
```
.config/karabiner/
```

This matches the default location at `~/.config/karabiner/` on macOS.

## Installation Instructions

### 1. Install Karabiner-Elements
Download and install Karabiner-Elements 13.7.0 or a compatible version:
- Visit the [Karabiner-Elements GitHub releases page](https://github.com/pqrs-org/Karabiner-Elements/releases)
- Download version 13.7.0 or newer
- Install the package

### 2. Restore Configuration
To restore this configuration:

```bash
# Backup your existing configuration (if any)
mv ~/.config/karabiner ~/.config/karabiner.bak

# Clone this repository
git clone https://github.com/felixwulf7/karabinerconfig.git

# Copy the configuration to your home directory
cp -R karabinerconfig/.config/karabiner ~/.config/

# Restart Karabiner-Elements
killall Karabiner-Elements
open /Applications/Karabiner-Elements.app
```

## Contents
- Main configuration file (`karabiner.json`)
- Complex modifications
- Automatic backups
- Custom profiles

## Notes
- Some settings may be specific to my keyboard layout and preferences
- Modify as needed for your specific hardware
