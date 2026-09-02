# 🎮 Games

A collection of small, lightweight web games and game-related projects.

The repository is intended as a home for simple games that can be played in a web browser, with an emphasis on mobile-friendly interfaces, minimal dependencies, and easy access.

## 📁 Repository Structure

```text
Games/
│
├── README.md
│
├── Yatzy-pwa/
│   ├── index.html
│   ├── manifest.webmanifest
│   ├── sw.js
│   └── icons/
│       ├── icon-192.png
│       └── icon-512.png
│
└── future-games/
    └── ...
```

Each game or project is kept in its own subfolder so that it can be developed, hosted, and maintained independently.

## 🎲 Games

### Yatzy PWA

**Location:** `Yatzy-pwa/`

A two-player Yatzy scorecard designed primarily for mobile devices.

#### Yatzy
- 5 dice
- Standard upper section
- Standard lower section
- 63-point upper-section bonus threshold, bonus 50
- Yatzy 50 points

#### Max Yatzy
- 6 dice
- 75-point upper-section bonus threshold, bonus 50
- Yatzy 100 points

## 🌐 Web Games

The projects in this repository are designed to run directly in modern web browsers.

Where supported, games may also be installed as Progressive Web Apps and launched from a mobile device like a normal application.

## 📱 Mobile First

The games are designed with smaller screens in mind.

The intention is to make them:

- Easy to use on phones
- Comfortable to interact with using touch
- Responsive across different screen sizes
- Simple enough to use while actually playing the game

## 🧩 Technology

The projects are primarily built using standard web technologies:

- **HTML** — structure
- **CSS** — responsive layout and styling
- **JavaScript** — game logic and interaction
- **PWA APIs** — installation and offline support where applicable
- **LocalStorage** — local game data persistence where applicable

The projects aim to avoid unnecessary frameworks and dependencies where a small standalone web application is sufficient.

## 🚀 Adding New Games

New games should normally be added as their own subfolder under `Games/`.

For example:

```text
Games/
├── README.md
│
├── Yatzy-pwa/
│   └── ...
│
├── Dice-game/
│   └── ...
│
├── Card-game/
│   └── ...
│
└── Puzzle-game/
    └── ...
```

Each project can contain its own HTML, CSS, JavaScript, images, icons, and PWA files as needed.

## 🎯 Goals

The repository is primarily a playground for small web games and experiments.
And learning to vibe code games.

## 📄 License

Unless otherwise specified in an individual project, these games are intended for personal and experimental use.
