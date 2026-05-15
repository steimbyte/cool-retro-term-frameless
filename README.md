# cool-retro-term

|> Default Amber|C:\ IBM DOS|$ Default Green|
|---|---|---|
|![Default Amber Cool Retro Term](https://user-images.githubusercontent.com/121322/32070717-16708784-ba42-11e7-8572-a8fcc10d7f7d.gif)|![IBM DOS](https://user-images.githubusercontent.com/121322/32070716-16567e5c-ba42-11e7-9e64-ba96dfe9b64d.gif)|![Default Green Cool Retro Term](https://user-images.githubusercontent.com/121322/32070715-163a1c94-ba42-11e7-80bb-41fbf10fc634.gif)|

## Description
cool-retro-term is a terminal emulator which mimics the look and feel of the old cathode tube screens.
It has been designed to be eye-candy, customizable, and reasonably lightweight.

It uses the QML port of qtermwidget (Konsole): https://github.com/Swordfish90/qmltermwidget.

This terminal emulator works under Linux and macOS and requires Qt6.

Settings such as colors, fonts, and effects can be accessed via context menu.

## Screenshots
![Image](https://i.imgur.com/TNumkDn.png)
![Image](https://i.imgur.com/hfjWOM4.png)
![Image](https://i.imgur.com/GYRDPzJ.jpg)

---

## 🔧 Frameless Mode (steimer mod)

This fork adds **frameless window support** - remove title bar and window decorations for a cleaner look!

### Screenshot

**Frameless Mode (no window decorations):**
![Cool Retro Term Frameless](https://i.imgur.com/sELnfzO.png)

### How to Enable

1. Open Cool Retro Term
2. Go to **Settings** → **General**
3. Uncheck **Window Decorations**
4. Restart the application

The setting is saved automatically and persists across sessions.

---

## Install

### Pre-built

Grab the latest release from the Releases page or install via your package manager:

```bash
# Arch Linux
sudo pacman -S cool-retro-term

# macOS (Homebrew)
brew install --cask cool-retro-term
```

### Build from Source

#### Prerequisites

- Qt6 (Qt5 is not supported)
- CMake or qmake
- C++ compiler

#### Build Steps

```bash
# Clone the repository
git clone https://github.com/steimbyte/cool-retro-term-frameless.git
cd cool-retro-term-frameless

# Initialize submodules
git submodule update --init --recursive

# Build with Qt6
/usr/lib/qt6/bin/qmake
make -j$(nproc)

# Install
sudo make install
```

### Building (Original Repository)

Check out the wiki and follow the instructions on how to build it on [Linux](https://github.com/Swordfish90/cool-retro-term/wiki/Build-Instructions-(Linux)) and [macOS](https://github.com/Swordfish90/cool-retro-term/wiki/Build-Instructions-(macOS)).

---

## Original Project

https://github.com/Swordfish90/cool-retro-term
