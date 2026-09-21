# Cuphead CDV

A **Cuphead** fangame built on the **Booty5/Cordova** engine.

## Description

Cuphead CDV is a fangame originally created by **IdrewDev** and currently continued and maintained by **Lax Studios**, built with Booty5 (an HTML5/Canvas-based 2D game engine) and packaged with Cordova for cross-platform deployment.

## Features

- Full achievement system with 28 achievements
- Multilingual support across 7 languages
- In-scene achievements panel
- Toast notifications on achievement unlock
- Built on the Booty5/Cordova engine, sharing its technical base with [Pac-Man Dash](https://github.com/LaxyDev64/pacman-dash)

## Tech Stack

- **Engine:** Booty5 (HTML5/Canvas)
- **Packaging:** Apache Cordova
- **Language:** JavaScript

## Installation

```bash
git clone https://github.com/LaxyDev64/Cuphead-CDV.git
cd Cuphead-CDV
npm install
```

## Running

```bash
cordova run browser
```

Or open `index.html` directly in a browser for quick testing.

## Build

```bash
cordova build android
cordova build ios
```

##  Project Structure

```
Cuphead-CDV/
├── www/              # Game source code (assets, scripts, scenes)
├── config.xml        # Cordova configuration
├── package.json
└── README.md
```

## Credits

- **Original creator:** IdrewDev
- **Maintenance and continuation:** Lax Studios ([LaxyDev64](https://github.com/LaxyDev64))

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

## License

This project is a non-commercial fan project. Cuphead is a registered trademark of Studio MDHR. All original code in this repository is distributed under the MIT license (adjust as appropriate).

##  Related Projects

- [Pac-Man Dash](https://github.com/LaxyDev64/pacman-dash) — Lax Studios endless runner built on the same Booty5/Cordova engine
